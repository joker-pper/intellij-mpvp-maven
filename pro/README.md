
# IDEA插件Maven With Me Pro蹬蹬蹬登场啦，Maven开发版本管理小助手！！！

[![jetbrains_pro_plugin_downloads](https://img.shields.io/jetbrains/plugin/d/29269-maven-with-me-pro-mpvp-?label=%E2%AD%90%20Maven%20With%20Me%20Pro%20downloads&labelColor=ff4c41&color=green)](https://plugins.jetbrains.com/plugin/29269-maven-with-me-pro-mpvp-)
[<img alt="lang-中文" src="https://img.shields.io/badge/lang-中文-success"/>](README.md)
[<img alt="lang-English" src="https://img.shields.io/badge/lang-English-success"/>](README_en.md)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?logo=github&logoColor=white)](https://joker-pper.github.io/intellij-mpvp-maven/pro)
[<img alt="LICENSE" src="https://img.shields.io/badge/LICENSE-blue"/>](../docs/LICENSE_Page.md)

<div align="center" style="text-align: center;">
    <img alt="visitors" style="max-width: 100%;" src="https://count.getloli.com/get/@joker-pper.intellij-mpvp-maven?theme=original-new" />
</div>


## 💡前言

<b>工欲善其事必先利其器！ 轻便快捷是初心，势必为节省您的大量时间和心力而前行！让更多的时间和价值留在更重要的地方！！！</b><br/><br/>
<b>希望它能成为一款真正有价值的插件，避免大家花费更多的精力和心力在这些繁琐的流程中。当然这也需要您的支持，以便我们提供更好的服务和迭代，利他和利己不是可以共存的嘛~ 让我们一起走得更远！</b><br/>

<hr/>

<p style="font-size: 20px; font-weight: bold; color:red;">
欢迎大家加入交流群，不仅能在第一时间获取最新插件资源，还能一起交流学习！
</p>

QQ交流群: [550996296（点击加群）](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=50F30oecs4iVEfMBlRK4fhfLIzLlV6-t&authKey=i%2BrfuFb1IrbqEmE3QT5GCOF75A0LXsoriZN9951IbY7eezZpoQgvskOkK513z2Bf&noverify=0&group_code=550996296)

微信交流群: 在微信公众号 <a style="color: rgb(255, 76, 65);" href="https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzkyODk0MTA1MA==&scene=124#wechat_redirect" target="_blank">“新程快咖员”</a>（<a href="https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzkyODk0MTA1MA==&mid=2247483700&idx=1&sn=2a00414552461b2235b1d4b5b6878f16&send_time=" target="_blank">点击查看二维码</a>）直接留言<span textstyle="" style="color: rgb(255, 76, 0)">“微信群”</span>即可获取


<br/>
<hr/>

## 🌟IDEA 插件Maven With Me Pro(MPVP) 是什么？

<p>Maven Project Version Plugin, Support Quick Update Version And Show Project Version And Search Project Version And Quick Generate Badges For Common Project Version And supporting synchronization of SDK and other configurations.</p>

<p>Note: If you are using Gradle, the corresponding IDEA plugin is Gradle With Me Pro(GPVP)</p>

<p>Maven项目版本插件，可用于版本快速傻瓜式升级及项目版本展示和项目版本搜索并支持快速生成常见项目版本的徽章及SDK相关配置同步等功能。</p>

<p>注：若您使用的是Gradle，对应的IDEA 插件为 Gradle With Me Pro(GPVP)。</p>


## ✨核心功能

### 支持maven项目版本快速升级/回退

无论是快照版还是release版，输入后提交一键轻松帮您搞定版本值升级或回退（再也不用头疼和花费大量时间调整版本值啦）。还会为您展示修改的具体细节~ 简化您的工作流程，为您节省大量宝贵时间！

### 支持maven项目版本展示

可直接在项目视图中展示版本值，一眼便能知晓当下版本~ 并提供自定义展示规则能力。

### 支持maven/gradle项目依赖版本搜索

支持查询中央仓库最新依赖版本，也可以快速查询Nexus仓库(远程/私服)依赖版本。简化您的工作流程，为您节省大量宝贵时间！<br/>
提供便捷式搜索能力(Maven pom配置或Gradle依赖配置粘贴后即可查询，也可通过关键字进行查询)， 一键复制依赖坐标，
<span style="color: rgb(255, 76, 65);">一键访问文件目录（兼容Nexus低版本）</span>，<span style="color: rgb(255, 76, 65);">一键加载更新时间（兼容Nexus低版本）</span>，快速查看版本详情页等，欢迎上手体验~

### 支持maven/gradle项目版本徽章生成

支持快速生成常见Maven/Gradle项目版本的徽章 (依赖<span style="color: rgb(255, 76, 65);">shields.io</span>能力)。<span style="color: rgb(255, 76, 65);">提供常见参数使用，可快速自定义文本及颜色。</span>提供支持<span style="color: rgb(255, 76, 65);">groupId+artifactId快速输入能力</span>(如Maven pom配置或Gradle依赖配置粘贴即可)，并<span style="color: rgb(255, 76, 65);">内置常用徽章的跳转链接</span>(如发布到中央仓库release jar的版本链接)及<span style="color: rgb(255, 76, 65);">自定义跳转链接</span>，为您徽章的生成<span style="color: rgb(255, 76, 65);">提供一定的便捷</span>~

### 支持项目配置同步功能

自动同步<span style="color: rgb(255, 76, 65);">JDK</span>、语言level规范等配置功能！无论是个人开发还是团队协作，<span style="color: rgb(255, 76, 65);">一人配置，全员共享！</span>(需要提交配置到远程仓库) <br/>

无论是在<span style="color: rgb(255, 76, 65);">项目打开</span>，还是<span style="color: rgb(255, 76, 65);">Git clone、Git分支切换、Git还原等场景</span>下，<span style="color: rgb(255, 76, 65);">自动识别切换</span>到对应的<span style="color: rgb(255, 76, 65);">JDK版本</span>及配置！！！进一步<span style="color: rgb(255, 76, 65);">统一团队SDK规范</span>，并节省团队或个人需多次手动配置IDE环境等繁琐步骤及时间！！！ <br/>

其他说明：JDK Home Path中的 ~ 代表为用户主目录，用于动态识别出不同用户名下的统一路径。

<span style="color: red">注：</span>如要了解更多，[请点击这里查看特性详请](../docs/FeaturesDetail.md)


## 如何找到操作菜单？

Tools > Maven Project Version

![how-to-find-plugin-menu](https://joker-pper.github.io/intellij-mpvp-maven/picture/how-to-find-plugin-menu.png)

## 如何配置Nexus访问权限？

[IDEA插件Maven With Me Pro如何配置Nexus访问权限？](../docs/how-to-configure-nexus-access-permissions_zh.md)

## 其他

### conf.properties配置文件

可用于进行个性化项的配置

+ 全局配置: 用户主目录/mpvp/conf.properties

+ 项目配置: 用户项目工作目录/.idea/mpvp/conf.properties (优先级最高)

支持配置如下：


```
# 自定义使用语言
#my.language=zh_CN
#my.language=zh_TW
#my.language=en

# pom-path是否进行转换
format.pom-path.prettify=true

# pom-path中替换用户主目录的字符串
format.pom-path.user.home.str=~

# 序列号是否脱敏
sensitive-data.machine_serial_numbers=true

# 搜索nexus3查看远程仓库使用新url (配置值存在多个时用,分割) -- 2.1.x新增
#search.nx3.repository-version-use-new-url=http://localhost:8081/
#search.nx3.repository-version-use-new-url=http://localhost:8081/,http://localhost:8083/

# 搜索nexus缓存保存周期（单位：分钟，配置值应 > 0，未配置或不合法时使用默认值 360）-- 2.1.x新增
#search.nx.cache-save-period=360

# 用户私服release版查询结果缓存有效期，未配置时默认30分钟 （单位：分钟，配置值应 > 0 且 <= 360。当未配置或 < 1 时使用默认值，当值 > 最大值时则使用默认最大值）
search.user-repository-search-result.release-cache-period=30

# 用户私服快照版查询结果缓存有效期，未配置时默认1分钟 （单位：分钟，配置值应 > 0 且 <= 360。当未配置或 < 1 时使用默认值，当值 > 最大值时则使用默认最大值）
search.user-repository-search-result.snapshots-cache-period=1

# 复制gradle坐标是否使用Kotlin格式，未配置时默认false
#gradle-coordinate-copy-with-kotlin=false

# 是否启用支持（通过键盘复制快捷键）选中多行复制（保持原有机制）及支持复制单行单列的结果值，未配置时默认false
#enable-search-version-table-input-key-enhance-copy=true

```

### 系统内置语言

+ zh         中文
+ zh_CN      简体中文（中国）
+ zh_TW      中文（台湾）
+ en         英文

#### 如何指定当前使用的语言？

可通过系统默认语言，也可在conf.properties中进行指定要使用的语言


## 联系我们

如果您有任何问题或建议，可以通过以下方式：

提交 [Github Issues](https://github.com/joker-pper/intellij-mpvp-maven/issues)
<br/>
<br/>
QQ交流群: [550996296（点击加群）](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=50F30oecs4iVEfMBlRK4fhfLIzLlV6-t&authKey=i%2BrfuFb1IrbqEmE3QT5GCOF75A0LXsoriZN9951IbY7eezZpoQgvskOkK513z2Bf&noverify=0&group_code=550996296)
<br/>
<br/>
微信交流群: 在微信公众号 <a style="color: rgb(255, 76, 65);" href="https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzkyODk0MTA1MA==&scene=124#wechat_redirect" target="_blank">“新程快咖员”</a>（<a href="https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzkyODk0MTA1MA==&mid=2247483700&idx=1&sn=2a00414552461b2235b1d4b5b6878f16&send_time=" target="_blank">点击查看二维码</a>）直接留言<span textstyle="" style="color: rgb(255, 76, 0)">“微信群”</span>即可获取
<br/>
<br/>
公众号: <a style="color: rgb(255, 76, 65);" href="https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzkyODk0MTA1MA==&scene=124#wechat_redirect" target="_blank">“新程快咖员”</a>（<a href="https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzkyODk0MTA1MA==&mid=2247483700&idx=1&sn=2a00414552461b2235b1d4b5b6878f16&send_time=" target="_blank">点击查看二维码</a>）
<br/>
<br/>
Email: [yyc_xincheng@163.com](mailto:yyc_xincheng@163.com)
<br/>
<br/>
