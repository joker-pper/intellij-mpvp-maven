# IDEA plugin Maven With Me Pro is now available, Maven development version management assistant!!!

[![jetbrains_pro_plugin_downloads](https://img.shields.io/jetbrains/plugin/d/29269-maven-with-me-pro-mpvp-?label=%E2%AD%90%20Maven%20With%20Me%20Pro%20downloads&labelColor=ff4c41&color=green)](https://plugins.jetbrains.com/plugin/29269-maven-with-me-pro-mpvp-)
[<img alt="lang-中文" src="https://img.shields.io/badge/lang-中文-success"/>](README.md)
[<img alt="lang-English" src="https://img.shields.io/badge/lang-English-success"/>](README_en.md)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?logo=github&logoColor=white)](https://joker-pper.github.io/intellij-mpvp-maven/pro)
[<img alt="LICENSE" src="https://img.shields.io/badge/LICENSE-blue"/>](../docs/LICENSE_Page.md)

<div align="center" style="text-align: center;">
    <img alt="visitors" style="max-width: 100%;" src="https://count.getloli.com/get/@joker-pper.intellij-mpvp-maven?theme=original-new" />
</div>


## 💡Preface

<b>To do a good job, one must first sharpen their tools! Lightweight and fast is our original intention, and we will definitely move forward to save you a lot of time and effort! Let more time and value stay in more important places!!!</b><br/>
<b>I hope it can become a truly valuable plugin, avoiding everyone from spending more energy and effort on these tedious processes. Of course, this also requires your support so that we can provide better services and iterations. Altruism and self-interest can coexist. Let's go further together! </b><br/>

<hr/>

<p style="font-size: 20px; font-weight: bold; color:red;">
Welcome everyone to join the communication group, not only can you get the latest plugin resources in the first time, but you can also communicate and learn together!
</p>

QQ communication group:  [Click to add to group](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=50F30oecs4iVEfMBlRK4fhfLIzLlV6-t&authKey=i%2BrfuFb1IrbqEmE3QT5GCOF75A0LXsoriZN9951IbY7eezZpoQgvskOkK513z2Bf&noverify=0&group_code=550996296)

WeChat communication group: On the WeChat official account <a style="color: rgb(255, 76, 65);" href="https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzkyODk0MTA1MA==&scene=124#wechat_redirect" target="_blank">“新程快咖员”</a> (<a href="https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzkyODk0MTA1MA==&mid=2247483700&idx=1&sn=2a00414552461b2235b1d4b5b6878f16&send_time=" target="_blank">Click to view QR code</a>) Leave a message <span style="color: rgb(255, 76, 65);">"WeChat group"</span> to get it



<br/>
<hr/>

## 🌟What is IDEA plugin Maven With Me Pro(MPVP) ?

<p>Maven Project Version Plugin, Support Quick Update Version And Show Project Version And Search Project Version And Quick Generate Badges For Common Project Version And supporting synchronization of SDK and other configurations.</p>

<p>Note: If you are using Gradle, the corresponding IDEA plugin is Gradle With Me Pro(GPVP)</p>

<p>Maven项目版本插件，可用于版本快速傻瓜式升级及项目版本展示和项目版本搜索并支持快速生成常见项目版本的徽章及SDK相关配置同步等功能。</p>

<p>注：若您使用的是Gradle，对应的IDEA 插件为 Gradle With Me Pro(GPVP)。</p>


## ✨Features

### Support quick upgrade/rollback of Maven project version

Whether it's a snapshot version or a release version, simply input and submit with one click to easily help you upgrade or roll back version values (no longer have to worry and spend a lot of time adjusting version values). We will also show you the specific details of the modifications~Simplify your workflow and save you a lot of valuable time!


### Support Maven project version display

Version values can be displayed directly in the project view, and the current version can be known at a glance, providing the ability to customize display rules.

### Support Maven/Gradle project dependency version search

Support querying the latest dependency versions of the central repository, as well as quickly querying the dependency versions of the Nexus repository (remote/private). Simplify your workflow and save you a lot of valuable time! <br/>
Provide convenient search capabilities (Maven pom configuration or Gradle dependency configuration can be pasted and queried, or searched by keywords), one click copying of dependency coordinates,
<span style="color: rgb(255, 76, 65);">One click access to file directory (compatible with lower versions of Nexus)</span>,<span style="color: rgb(255, 76, 65);">One click loading update time (compatible with lower versions of Nexus)</span>, quick view of version details page, etc. Welcome to experience it~

### Support Generate badges for Maven/Gradle project versions

Support for quickly generating badges for common Maven/Gradle project versions (relying on <span style="color: rgb(255, 76, 65);">shields. io</span> capability).  <span style="color: rgb(255, 76, 65);">Provides common parameter usage for quickly customizing text and colors. </span>Provide support for <span style="color: rgb(255, 76, 65);">groupId+artifactId quick input capability</span>(such as Maven pom configuration or Gradle dependency configuration pasting), and <span style="color: rgb(255, 76, 65);">built-in jump links for commonly used badges</span>(such as version links published to the central repository release jar) and <span style="color: rgb(255, 76, 65);">custom jump links</span> to generate badges for you <span style="color: rgb(255, 76, 65);">Provide certain convenience</span>~

### Support Project Settings Synchronous

Automatically synchronize JDK, language level specifications, and other configuration features! Whether it's individual development or team collaboration, one person configuration, shared by all! (Need to submit configuration to remote repository)<br/>

Automatically recognize and switch to the corresponding JDK version and configuration, whether in project opening, Git clone, Git branch switching, Git rollback, or other scenarios!!! Further unify the team SDK specifications and save the tedious steps and time required for teams or individuals to manually configure IDE environments multiple times!!!  <br/>

Other instructions: The '~' in JDK Home Path represents the user's home directory, which is used to dynamically identify a unified path under different usernames.

<span style="color: red">Note:</span> To learn more, [please click here for detailed features](../docs/FeaturesDetail_en.md)


## How to find the operation menu?

Tools > Maven Project Version

![how-to-find-plugin-menu](../picture/how-to-find-plugin-menu.png)


## How to configure Nexus access permissions?

[How to configure Nexus access permissions for IDEA plugin Maven With Me Pro?](../docs/how-to-configure-nexus-access-permissions_en.md)


## Other

### conf.properties

Can be used for configuring personalized items

+ global configuration: user home/mpvp/conf.properties

+ project configuration: user project work dir/.idea/mpvp/conf.properties (Highest priority)


The supported configurations are as follows:

```
# customize language usage
#my.language=zh_CN
#my.language=zh_TW
#my.language=en

# pom-path format to prettify?
format.pom-path.prettify=true

# pom-path format to replace the string of the user home 
format.pom-path.user.home.str=~

# machine serial numbers to desensitize?
sensitive-data.machine_serial_numbers=true

# search for Nexus3.x to view new url for remote repository version usage (when there are multiple values use , split) -- 2.1.x added
#search.nx3.repository-version-use-new-url=http://localhost:8081/
#search.nx3.repository-version-use-new-url=http://localhost:8081/,http://localhost:8083/

# search nexus cache save period (Unit: minutes, value should be > 0, use default value 360 when not configured or illegal)-- 2.1.x added
#search.nx.cache-save-period=360

# user's private nexus server release query result cache period, and 30 minutes by default when not configured (Unit: minutes, value should be > 0 and <= 360. When not configured or < 1, use default value; when value > maximum value, use default maximum value)
search.user-repository-search-result.release-cache-period=30

# user's private nexus server snapshots query result cache period, and 1 minutes by default when not configured（Unit: minutes, value should be > 0 and <= 360. When not configured or < 1, use default value; when value > maximum value, use default maximum value)
search.user-repository-search-result.snapshots-cache-period=1

# Copy Gradle coordinates in Kotlin format, default to false if not configured
#gradle-coordinate-copy-with-kotlin=false

# Whether to enable support (Copy shortcut keys through keyboard) for selecting multi row copying (maintaining the original mechanism) and support for copying single row and single column result values. If not configured, default to false
#enable-search-version-table-input-key-enhance-copy=true

```

### Internal System Language

+ zh         Chinese
+ zh_CN      Simplified Chinese（China）
+ zh_TW      Chinese（Taiwan）
+ en         English

#### How to Specify The Current Used Language?

You can use the default language of the system or specify the language to be used in conf.properties



## Contact Us

If you have any questions or suggestions, you can do so through the following methods:

Submit [Github Issues](https://github.com/joker-pper/intellij-mpvp-maven/issues)
<br/>
<br/>
QQ communication group: [Click to add to group](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=50F30oecs4iVEfMBlRK4fhfLIzLlV6-t&authKey=i%2BrfuFb1IrbqEmE3QT5GCOF75A0LXsoriZN9951IbY7eezZpoQgvskOkK513z2Bf&noverify=0&group_code=550996296)
<br/>
<br/>
WeChat communication group: On the WeChat official account <a style="color: rgb(255, 76, 65);" href="https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzkyODk0MTA1MA==&scene=124#wechat_redirect" target="_blank">“新程快咖员”</a> (<a href="https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzkyODk0MTA1MA==&mid=2247483700&idx=1&sn=2a00414552461b2235b1d4b5b6878f16&send_time=" target="_blank">Click to view QR code</a>) Leave a message <span style="color: rgb(255, 76, 65);">"WeChat group"</span> to get it
<br/>
<br/>
WeChat official account: <a style="color: rgb(255, 76, 65);" href="https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzkyODk0MTA1MA==&scene=124#wechat_redirect" target="_blank">“新程快咖员”</a> (<a href="https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzkyODk0MTA1MA==&mid=2247483700&idx=1&sn=2a00414552461b2235b1d4b5b6878f16&send_time=" target="_blank">Click to view QR code</a>)
<br/>
<br/>
Email: [yyc_xincheng@163.com](mailto:yyc_xincheng@163.com)
<br/>
<br/>
