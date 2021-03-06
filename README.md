# vue-cli-plugin-publicpath

[![Build Status](https://travis-ci.org/longshihui/vue-cli-plugin-publicpath.svg?branch=master)](https://travis-ci.org/longshihui/vue-cli-plugin-publicpath) [![](https://img.shields.io/npm/v/vue-cli-plugin-publicpath.svg)](https://www.npmjs.com/package/vue-cli-plugin-publicpath) [![](https://img.shields.io/npm/l/vue-cli-plugin-publicpath.svg)](https://www.npmjs.com/package/vue-cli-plugin-publicpath)

rewrite assets publicPath in production env

[中文文档](./README_ZH.md)

## Install

**vue cli**

```
vue add publicpath
```

**yarn**

```
yarn add vue-cli-plugin-publicpath --dev
```

**npm**

```
npm i vue-cli-plugin-publicpath --save-dev
```

## Configuration

**vue.config.js**

```
module.exports = {
    baseUrl: '//js.cdn.com',  // js publicPath
    pluginOptions: {
        publicPath: {
            css: '',
            images: '',
            svg: '',
            media: '',
            fonts: ''
        }
    }
}
```

See [this file](./service/options-defaults.js) for config options.



