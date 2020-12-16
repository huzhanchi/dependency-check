## 整体介绍
dependency-check 是owsap下对java漏洞组件依赖的检查，不过官方只支持本地模式，即漏洞库本地更新，本地检查。我们做了本地轻量级的plugin，服务端做复杂检查的改进，同时能够阻断包含严重漏洞业务构建流程

* 改进后架构

![image](https://github.com/huzhanchi/dependency-check/blob/main/images/dependency-check.png)

* 构建

![image](https://github.com/huzhanchi/dependency-check/blob/main/images/log1.png)