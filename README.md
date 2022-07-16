# zb-snippets

```
some snippets for visual studio code
```

[![](https://vsmarketplacebadge.apphb.com/version/hollowtree.vue-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)
[![](https://vsmarketplacebadge.apphb.com/installs/hollowtree.vue-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)

--------------------------------------

| Prefix |
| ------ |
| `resetCss` |

```
html {
    height: 100%
}
```

--------------------------------------
### Supported languages
* vue(.vue)
* HTML(.html)
* javascript(.js)
* typescript(.ts)
* pug(.pug)

--------------------------------------
##### 2020/07/27 (0.1.12)
* Add snippets and fix bugs

--------------------------------------
#### 开发VsCode插件流程 ####
1. 全局下载模版生成插件
2. 生成模版
3. 全局下载插件发布控件
4. 打包插件

```
1. npm install -g yo generator-code
2. yo code
3. npm install -g vsce
4. vsce package
```
