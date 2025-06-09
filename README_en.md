# MPVP(maven) - Maven Project Version Plugin

[![jetbrains_plugin_downloads](https://img.shields.io/jetbrains/plugin/d/24176-mpvp-maven?label=plugin%20downloads&color=green)](https://plugins.jetbrains.com/plugin/24176-mpvp-maven-)
[<img alt="lang-中文" src="https://img.shields.io/badge/lang-中文-success"/>](./README.md)
[<img alt="lang-English" src="https://img.shields.io/badge/lang-English-success"/>](./README_en.md)
[<img alt="LICENSE" src="https://img.shields.io/badge/LICENSE-blue"/>](./LICENSE.md)


Maven项目版本插件，可用于版本快速傻瓜式升级及项目版本展示和项目版本搜索.
<br/>
Maven Project Version Plugin, Support Quick Update Version And Show Project Version And Search Project Version.

## Preface

工欲善其事必先利其器！想必大家在使用maven时会经常碰到项目版本升级和依赖版本升级的问题吧。针对占用大家大量时间以及大家经常使用遇到的痛点，这款插件诞生了！！！
轻松帮您解决搜索依赖困扰和升级版本困扰！ 轻便快捷是初心，势必为节省您的大量时间和心力而前行！让更多的时间和价值留在更重要的地方！！！

To do a good job, one must first sharpen their tools! I believe everyone often encounters issues with project version upgrades and dependency version upgrades when using Maven. This plugin has been born to address the pain points that consume a lot of everyone's time and are frequently encountered during use!!!
Easily help you solve search dependency and upgrade version problems! Lightweight and fast is our original intention, and we will definitely move forward to save you a lot of time and effort! Let more time and value stay in more important places!!!

## Update plan

version: <span style="color: red">2.3.x</span>

expected release time: <span style="color: red">250715</span>

details: [click here to go](docs/Next.md)

## Discounted activities

[🔥 idea插件MPVP(Maven)限时618优惠活动来啦，最高可享5折！（最低可至每月不到￥4！买奶茶的钱就能换一整年高效开发
！快来上车！！！）](https://mp.weixin.qq.com/s/Gemngf1FW9h2EKEcn702Pw)


## How to activate it?

Search WeChat official account <a style="color: rgb(255, 76, 65);" href="https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzkyODk0MTA1MA==&scene=124#wechat_redirect" target="_blank">“新程快咖员”</a> (<a href="https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzkyODk0MTA1MA==&mid=2247483700&idx=1&sn=2a00414552461b2235b1d4b5b6878f16&send_time=" target="_blank">Click to view QR code</a>) Operate according to the menu link

<span style="color: red">Note: </span>If there is any problem, you can send a message directly on the WeChat official account to leave a message

In addition to testing the plugin directly after its release, you can also apply for a free trial! Just follow the instructions on the WeChat official account.


## How to find the operation menu?

Tools > Maven Project Version

![how-to-find-plugin-menu](picture/how-to-find-plugin-menu.png)

## Features

### Maven Project Version Update

Whether it's a snapshot version or a release version, simply input and submit with one click to easily help you upgrade or roll back version values (no longer have to worry and spend a lot of time adjusting version values). We will also show you the specific details of the modifications~Simplify your workflow and save you a lot of valuable time!

<b>Note:</b>

Firstly, it is recommended that everyone use a version management tool (backup) when modifying versions. Whether or not this plugin is used for version changes, quick recovery or rollback can be performed in case of problems!!!

This feature relies on Maven data read by Idea. If your POM has changed, you need to refresh it before using this feature.

<span style="color: #cb1414;">
If you are using it for the first time, we recommend that you first use the <b>version management tool (backup)</b> to verify whether the plugin is perfectly compatible with your project scenario (refer to the previous prompt). <br/><br/>
When there is a major adjustment to this feature (in subsequent versions starting from 25.06.01), we will first attempt to release a version with the plugin "xxx-beat" and display the feature update identifier (including the update date) on the user interface. If you find that the feature update identifier has changed after upgrading the version, you will need to re verify it again to ensure that the upgraded feature meets expectations and avoid any inconvenience. 
If you find any problems, you can report them and temporarily revert back to the version before the change. <br/>
</span>
<br/>

<span style="color: rgb(255, 76, 65);">
If you encounter a situation where your project does not support it (possibly in a special scenario), please provide an example (desensitized) so that we can further improve the plugin together~
</span>
<br/>
<br/>

![update-version_en](picture/update-version_en.png)

![update-version-result_en](picture/update-version-result_en.png)


+ Default Strategy (recommend)

must have new version and changed version. <br/>

when version exist and matched will replace and support dependency version is special value (e.g: ${version} / [1.6, 1.8]) will continue replace.(If project version placeholders are used in dependencies, replacement will be skipped, but the corresponding variable property version value will be modified; if version range placeholders are used in dependencies, no processing will be done.) <br/>

+ General Strategy

must have new version.<br/>

when version exist and matched will replace. (Replace the version in the dependency with the new version to be applied) <br/>

+ Other

#### Support Must Same Version (Before)

If Checked: project or dependency version not equals project before replacement version will continue replace. <br/>

If Not Checked: new version will to replace.

#### Support Snapshot Version

If Checked: If the text value of the new version input box is a snapshot version (ending with -SNAPSHOT, case insensitive), it is directly considered as the new version. Otherwise, the text value of the new version input box is concatenated with -SNAPSHOT as the new version. <br/>

If Not Checked: The text value in the new version input box is directly used as the new version.


### Maven Project Version Show

You can directly display version values in the project view, knowing the current version at a glance and providing the ability to customize display rules (the ${v} is a fixed version value expression).

![show-version_en](picture/show-version_en.png)

#### project view

![show-version-project-view](picture/show-version-project-view.png)

#### structure view

![show-version-structure-view.png](picture/show-version-structure-view.png)

### Maven Project Version Search

Support querying the latest dependency versions of the Central Repository, as well as quickly querying the dependency versions of the Nexus Repository (remote/private).

Provide convenient search capabilities (Maven pom configuration or Gradle dependency configuration can be querying after pasting, or querying by keywords), 

One click copying of dependency coordinates, quick viewing of version detail pages, etc. Welcome to experience it~

Simplify your workflow and save you a lot of valuable time! (Continuously updated and optimized! Welcome to provide optimization suggestions~)

#### Central Repository

![search-version-central_en](picture/search-version-central_en.png)

![search-version-central-result_en](picture/search-version-central-result_en.png)

#### Nexus Repository (remote/private)

![search-version-nexus_en](picture/search-version-nexus_en.png)

![search-version-nexus-result_en](picture/search-version-nexus-result_en.png)

### Internationalization Support

Supports English, Chinese, Simplified Chinese (China), and Chinese (Taiwan)

## Other

### conf.properties

Can be used for configuring personalized items

+ global configuration: user home/mpvp/conf.properties

+ project configuration: user project work dir/.idea/mpvp/conf.properties (Highest priority)


The supported configurations are as follows:

```
# customize language usage
#my.language=zh_CN

# pom-path format to prettify?
format.pom-path.prettify=true

# pom-path format to replace the string of the user home 
format.pom-path.user.home.str=~

# machine serial numbers to desensitize?
sensitive-data.machine_serial_numbers=true

# search for Nexus3.x to view new url for remote repository version usage (when there are multiple values use , split) -- 2.1.x added
#search.nx3.repository-version-use-new-url=http://localhost:8081/
#search.nx3.repository-version-use-new-url=http://localhost:8081/,http://localhost:8083/

# search nexus cache save period（Unit: minutes, value should be > 0, use default value 360 when not configured or illegal）-- 2.1.x added
#search.nx.cache-save-period=360

```

### Internal System Language

+ zh         Chinese
+ zh_CN      Simplified Chinese（China）
+ zh_TW      Chinese（Taiwan）
+ en         English

#### How to Specify The Current Used Language?

You can use the default language of the system or specify the language to be used in conf. properties


## Use video sharing

[Using IDEA plugin MPVP(Maven) for multi module updates and version show](https://www.bilibili.com/video/BV18QoLYkEjD?vd_source=05374f268767300c92677818cbbdf95d)


## Contact Us

If you have any questions or suggestions, you can do so through the following methods:

+ Submit [Github Issues](https://github.com/joker-pper/intellij-mpvp-maven/issues)

+ QQ communication group: [550996296](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=50F30oecs4iVEfMBlRK4fhfLIzLlV6-t&authKey=i%2BrfuFb1IrbqEmE3QT5GCOF75A0LXsoriZN9951IbY7eezZpoQgvskOkK513z2Bf&noverify=0&group_code=550996296)

+ Email: [yyc_xincheng@163.com](mailto:yyc_xincheng@163.com)

