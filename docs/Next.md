

> What's Next? （版本号: 2.3.x 预计发布时间: 250715）

[返回主页](../README.md)

+ 优化中央仓库、Nexus仓库查询结果的版本值排序

+ 内网环境时可能无法获取序列号，增加启动日志进行输出

+ Maven更新项目版本界面增加功能更新标识（用来区分核心处理逻辑是否变更，以便用户识别“功能升级”来进行验证功能确保符合预期） 

    &nbsp;&nbsp;如: x1-25.01.01  x2-25.01.01 x3-25.01.01对应多个不同idea分支版本

+ Windows系统Maven版本搜索结果界面的按钮样式问题处理

+ 中央仓库查询支持查看文件目录 （试用版不支持）

+ Nexus仓库查询支持查询后默认自动加载版本值最大的前6条的详细（用于展示更新时间）

+ Nexus仓库查询支持操作“加载详细”按钮进行加载更新时间（试用版不支持）

+ Nexus仓库查询增加缓存（内存级）减少一定时间内的查询详细请求，默认用户级Nexus仓库缓存时效（snapshot为1分钟，release为30分钟），并提供可配置参数项调整（最小值为1分钟，最大值为360分钟）

+ Nexus3查询关键字参数修正：支持Extension(e)，不支持Packaging(p) 

+ 关键字输入内容优化，格式洁癖爱好者福利！（不同参数可换行， :后面支持添加单个空格），支持以下格式：

```
g:org.springframework.boot
a:spring-boot-parent
v:3.4.5

g: org.springframework.boot
a: spring-boot-parent
v: 3.4.5

g: org.springframework.boot

a: spring-boot-parent

v: 3.4.5
```

