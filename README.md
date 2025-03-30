# MPVP(maven)


[![jetbrains_plugin_download](https://img.shields.io/badge/jetbrains_plugin_download-blue)](https://plugins.jetbrains.com/plugin/24176-mpvp-maven-)


Maven项目版本插件，可用于版本快速傻瓜式升级及项目版本展示.  
Maven Project Version Plugin, Support Quick Update Version And Show Project Version.


## 特性

### Maven项目版本更新


+ 默认策略

必须存在新版本并且变更版本. <br/>

当版本存在且匹配时将会替换；并且支持依赖版本是特殊值 (e.g: ${version} / [1.6, 1.8]) 将会跳过替换.（依赖中使用项目版本占位符的会跳过替换，但会修改对应的变量属性版本值；如果依赖中使用的是版本范围的将不做处理） <br/>

+ 常规策略

必须存在新版本.<br/>

当版本存在并且匹配时将替换. （即将依赖中的版本替换为当前要应用的新版本）<br/>

+ 其他

支持必须同一版本 (变更前)

选中: 项目或依赖版本如果不等于替换之前的版本将跳过替换.

未选中: 新版本会直接替换.

### Maven项目版本显示

+ 项目视图展示

+ 结构视图展示

## 群组 Group
欢迎加qq群550996296进行交流 ~ <br/>
![](https://plugins.jetbrains.com/files/24176/60861-page/bf80e0ce-ec5c-48ae-aa72-7e37422dc6da)