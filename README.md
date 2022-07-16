# zb-snippets

```
some snippets for visual studio code
```

[![](https://vsmarketplacebadge.apphb.com/version/hollowtree.vue-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=zhubo.zb-snippets)
[![](https://vsmarketplacebadge.apphb.com/installs/hollowtree.vue-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=zhubo.zb-snippets)

![snippets in action](images/cssSnippet.gif)
![snippets in action](images/javascriptSnippet.gif)
--------------------------------------

| Prefix |
| ------ |
| `resetCss` |

```
html {
    height: 100%;
}

body {
    height: 100%;
    margin: 0;
    padding: 0;
}

a {
    text-decoration: none
}

ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

.clearfix::after {
    display: block;
    content: "";
    clear: both;
}
```
| Prefix |
| ------ |
| `slot` |
```
<template #default="scope">
    <span></span>
</template>
```

--------------------------------------
### Supported languages
* vue(.vue)
* HTML(.html)
* javascript(.js)
* typescript(.ts)
* pug(.pug)

--------------------------------------
##### 2022/07/16 (1.0.0)
* Frist version to try use

--------------------------------------
#### 开发VsCode插件流程 ####
1. 全局下载VS插件脚手架
2. 生成模版
3. 全局下载插件发布控件
4. * 打包插件
5. 先登陆 发布者
6. 在直接发布
7. 只能登陆后删除某个发布者，在平台不能删除

```
1. npm install -g yo generator-code
2. yo code
3. npm install -g vsce
4. vsce package
5. vsce login XX
6. vsce publish
7. vsce delete-publisher XX
```
