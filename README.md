# 熊猫约拍

> 项目链接 https://gitee.com/Panda_Appointment



## 项目背景

随着电商时代的蓬勃发展，线上网店逐渐取代了线下实体店，许多平面模特为线上服装店拍摄服装照片，以便于买家判断是否需要购买此服装，但是电商要通过中间商才能找到自己想要的模特和摄影师，中间商利用信息不对等赚取差价，电商既没有少花钱，模特和摄影师也没有多赚钱，效率不高，价格却不低。

每年六月都是毕业季，许多学校都会有拍毕业照的需要，甚至有些人会需要摄影师跟拍他毕业时学校的场景，以此来记录自己在这所学校的青葱岁月，便于以后追忆自己的似水年华。

因为中西文化的逐渐融合，婚纱照成为现在每个新婚家庭必不可少的东西，但是照相馆里的婚纱照又贵，时间又很容易冲突，摄影师的水平也不一定符合要求。

艺术照成为许多人保留自己的美好时光的不二选择，但是要找到符合自己要求的摄影团队，时间不会冲突是很困难的。

摄影成为了不少人的兴趣爱好，但是作为一个摄影萌新，如何挑选相机和镜头呢？如何调焦？如何处理照片？如何根据不同的场景调试相机？

为了解决以上的问题和需求，我们创建了熊猫约拍。熊猫约拍致力于打造一个功能更加完善，效率更高的摄影约拍平台，让顾客和模特、摄影师可以直接对话，减少中间商赚差价，让模特和摄影师可以有更加高效的交流。让菜鸟摄影师从中学到摄影的技巧。熊猫约拍的web端与移动端并行，既可用电脑访问，也可以用手机app。



## 项目简介

熊猫约拍，一个模特、摄影师预约拍照，效率更高的摄影约拍平台，让顾客和模特、摄影师可以直接发布需求或接单，让模特和摄影师可以有更加优质的预约拍照体验。不仅如此，用户还可以在熊猫约拍网站分享自己的作品、寻找拍照打卡地点、寻找摄影师或模特；网站还有贴心的订单排期和邮件提醒等功能。

熊猫约拍的后台采用微服务架构，使用Spring Cloud体系的技术，在服务器部署上，采用应用容器引擎Kubernetes和Docker集群部署，实现高可用。同时使用阿里云云效流水线技术实现持续集成、持续部署，自动化运维。

熊猫约拍搭建了多个客户端、分别有网站、安卓APP、微信公众号、微信小程序，多客户端为用户带来更多的选择，用户根据自己喜好选择一个客户端即可体验预约拍照。



## 功能点

图示：已完成 :o: 、未开始 :x: 、开发中 :computer: 

### 用户功能

#### 核心功能

|      功能       | 描述 | 完成度 |
| :-------------: | :--: | :----: |
|    预约拍照     |      |  :o:   |
|    发布预约     |      |  :o:   |
|    发布作品     |      |  :o:   |
|   打卡点推荐    |      |  :o:   |
| 模特/摄影师推荐 |      |  :o:   |
|   约拍排期表    |      |  :o:   |
|    短信通知     |      |  :o:   |
|    邮件通知     |      |  :o:   |
|    内容搜索     |      |  :o:   |

#### 非核心功能

|      功能      |               描述               | 完成度 |
| :------------: | :------------------------------: | :----: |
| 查询发布的约拍 |        查询自己发布的约拍        |  :o:   |
| 查询接单的约拍 |        查询自己接单的约拍        |  :o:   |
|  修改约拍内容  |      修改自己发布的约拍内容      |  :o:   |
|    删除约拍    |        删除自己发布的约拍        |  :o:   |
|    查询作品    |        查询自己发布的作品        |  :o:   |
|    删除作品    |        删除自己发布的作品        |  :o:   |
|  修改用户信息  | 修改头像、昵称、密码、身份信息等 |  :o:   |



### 管理员功能

|     功能     |        描述        | 完成度 |
| :----------: | :----------------: | :----: |
|   用户管理   |   对用户增删查改   |  :o:   |
| 预约拍照管理 | 对预约拍照增删查改 |  :o:   |
|   订单管理   |   对订单增删查改   |  :o:   |
|   作品管理   |   对作品增删查改   |  :o:   |
| 约拍类型管理 | 对约拍类型增删查改 |  :o:   |
|  轮播图管理  |  对轮播图增删查改  |  :o:   |
|  打卡点管理  |  对打卡点增删查改  |  :o:   |
| 统计用户城市 |    统计用户城市    |  :o:   |
|   统计约拍   |      统计约拍      |  :o:   |
|   统计作品   |      统计作品      |  :o:   |



### 共同功能

|   功能   |   描述   | 完成度 |
| :------: | :------: | :----: |
| 图片上传 | 图片上传 |  :o:   |





## 技术选型

### 后端

|            技术            |         名称          | 集成状态 |
| :------------------------: | :-------------------: | :------: |
|        Spring Boot         |  微服务应用基础框架   |   :o:    |
|        Spring Cloud        |    微服务集成框架     |   :o:    |
|    Spring Cloud Config     |    分布式配置中心     |   :o:    |
|    Spring Cloud Eureka     |    服务注册与发现     |   :o:    |
|     Spring Cloud Feign     |    声明式服务调用     |   :o:    |
|    Spring Cloud Ribbon     |    客户端负载均衡     |   :o:    |
|    Spring Cloud Hystrix    |     服务容错保护      |   :o:    |
|     Spring Cloud Zuul      |        API网关        |   :o:    |
|           Zipkin           |       链路追踪        |   :o:    |
|     Spring Boot Admin      |       服务监控        |   :o:    |
|           Maven            |     项目构建管理      |   :o:    |
|           Nexus3           |       Maven私服       |   :o:    |
|        阿里云 云效         | 持续集成CI/持续部署CD |   :o:    |
|           Gitee            |       代码仓库        |   :o:    |
| 阿里云云数据库RDS MySQL5.7 |        数据库         |   :o:    |
|           Druid            |     数据库连接池      |   :o:    |
|          MyBatis           |        ORM框架        |   :o:    |
|         PageHelper         |       分页插件        |   :o:    |
|       Redis Sentinel       |       哨兵集群        |   :o:    |
|         阿里云OSS          |      云对象存储       |   :o:    |
|          Swagger2          |    API文档生成工具    |   :o:    |
|        RESTful API         |    RESTful风格API     |   :o:    |
|           Nginx            |      代理服务器       |   :x:    |
|           Docker           |       应用容器        |   :o:    |
|         Kubernetes         |       应用容器        |   :o:    |
|       阿里云镜像仓库       |    阿里云镜像仓库     |   :o:    |
|           Scrapy           |    Python爬虫框架     |   :o:    |
|           OAuth2           |     身份/权限认证     |   :x:    |
|           Quartz           |    分布式任务调度     |   :o:    |
|       Elastic Search       |    分布式全文搜索     |   :o:    |
|          RabbitMQ          |       消息队列        |   :o:    |
|          短信通知          |                       |   :o:    |
|          邮件发送          |                       |   :o:    |
|         微信公众号         |                       |   :o:    |

### 前端

|        技术        |           名称            | 集成状态 |
| :----------------: | :-----------------------: | :------: |
|        HTML        |      超文本标记语言       |   :o:    |
|        CSS         |        层叠样式表         |   :o:    |
|     JavaScript     |       网页脚本语言        |   :o:    |
|       Vue.js       |         前端框架          |   :o:    |
|     VueRouter      |         前端路由          |   :o:    |
|        Vuex        |   状态管理（数据存储）    |   :o:    |
|     Element-UI     |       前端样式框架        |   :o:    |
|       Axios        |         网络请求          |   :o:    |
| vue-waterfall-easy |        瀑布流组件         |   :o:    |
|     vue2-admin     | 基于vue的后台管理前端框架 |   :o:    |
|      echarts       |         图表框架          |   :o:    |
|      uni-app       |     移动端跨平台框架      |   :o:    |

### 服务器

|         服务器          |     配置     |              使用              |
| :---------------------: | :----------: | :----------------------------: |
|   阿里云ECS - master    | 2核4G 5M带宽 |           k8s主节点            |
| 阿里云ECS - temp-node-1 | 1核2G 1M带宽 |           k8s子节点1           |
| 阿里云ECS - temp-node-2 | 1核2G 1M带宽 |           k8s子节点2           |
|   阿里云ECS - node-1    | 1核2G 1M带宽 | 部署config、eureka、zuul等组件 |
|      百度智能云BCC      | 2核4G 1M带宽 |      部署微服务服务提供者      |
|        华为云ECS        | 1核2G 1M带宽 |      部署Nexus3 Maven私服      |
|        腾讯云ECS        | 1核2G 1M带宽 |         部署Redis集群          |



## 软件架构

### 系统架构图

![熊猫约拍架构图](https://alanlee-image-bed.oss-cn-shenzhen.aliyuncs.com/note_images/20200324124354-537300.png)

### 部署架构图

![distributedSystem](https://images.gitee.com/uploads/images/2020/0310/113729_2c29a9dc_2231089.png)



## 项目代码仓库链接

|                             名称                             |                 描述                  |                             链接                             | 公开 |
| :----------------------------------------------------------: | :-----------------------------------: | :----------------------------------------------------------: | :--: |
|   [Panda_Appointment](https://gitee.com/Panda_Appointment)   |             熊猫约拍项目              |  https://gitee.com/organizations/Panda_Appointment/projects  | :o:  |
| [spring_cloud_micro_service_panda_appointment](https://gitee.com/Panda_Appointment/spring_cloud_micro_service_panda_appointment) |  熊猫约拍项目-该仓库只存放README文档  | https://gitee.com/Panda_Appointment/spring_cloud_micro_service_panda_appointment | :o:  |
| [panda-files](https://gitee.com/Panda_Appointment/panda-files) | 存放文件docker-compose.yml和shell文件 |       https://gitee.com/Panda_Appointment/panda-files        | :o:  |
| [panda-config-repo](https://gitee.com/Panda_Appointment/panda-config-repo) |   分布式配置中心-存放配置文件的仓库   |    https://gitee.com/Panda_Appointment/panda-config-repo     | :x:  |
| [panda-dependencies](https://gitee.com/Panda_Appointment/panda-dependencies) |            统一的依赖管理             |    https://gitee.com/Panda_Appointment/panda-dependencies    | :o:  |
| [panda-domain](https://gitee.com/Panda_Appointment/panda-domain) |       统一的领域模型（实体类）        |       https://gitee.com/Panda_Appointment/panda-domain       | :o:  |
| [panda-config](https://gitee.com/Panda_Appointment/panda-config) |            分布式配置中心             |       https://gitee.com/Panda_Appointment/panda-config       | :x:  |
| [panda-eureka](https://gitee.com/Panda_Appointment/panda-eureka) |         分布式服务注册与发现          |       https://gitee.com/Panda_Appointment/panda-eureka       | :o:  |
| [panda-admin](https://gitee.com/Panda_Appointment/panda-admin) |          分布式应用管理中心           |       https://gitee.com/Panda_Appointment/panda-admin        | :o:  |
| [panda-zipkin](https://gitee.com/Panda_Appointment/panda-zipkin) |            分布式链路追踪             |       https://gitee.com/Panda_Appointment/panda-zipkin       | :o:  |
| [panda-gateway](https://gitee.com/Panda_Appointment/panda-gateway) |              分布式网关               |      https://gitee.com/Panda_Appointment/panda-gateway       | :o:  |
| [panda-common](https://gitee.com/Panda_Appointment/panda-common) |             通用项目模块              |       https://gitee.com/Panda_Appointment/panda-common       | :o:  |
| [panda-common-microservice-component](https://gitee.com/Panda_Appointment/panda-common-microservice-component) |          微服务通用组件依赖           | https://gitee.com/Panda_Appointment/panda-common-microservice-component | :o:  |
| [panda-common-provider](https://gitee.com/Panda_Appointment/panda-common-provider) |           通用的服务提供者            |  https://gitee.com/Panda_Appointment/panda-common-provider   | :o:  |
| [panda-common-comsumer](https://gitee.com/Panda_Appointment/panda-common-comsumer) |           通用的服务消费者            |  https://gitee.com/Panda_Appointment/panda-common-comsumer   | :o:  |
| [panda-service-provider-user](https://gitee.com/Panda_Appointment/panda-service-provider-user) |            服务提供者-用户            | https://gitee.com/Panda_Appointment/panda-service-provider-user | :o:  |
| [panda-service-provider-image](https://gitee.com/Panda_Appointment/panda-service-provider-image) |            图片服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-image | :o:  |
| [panda-service-provider-TCarousel](https://gitee.com/Panda_Appointment/panda-service-provider-TCarousel) |           轮播图服务提供者            | https://gitee.com/Panda_Appointment/panda-service-provider-TCarousel | :o:  |
| [panda-service-provider-redis](https://gitee.com/Panda_Appointment/panda-service-provider-redis) |          缓存服务提供者redis          | https://gitee.com/Panda_Appointment/panda-service-provider-redis | :o:  |
| [panda-service-provider-appointment](https://gitee.com/Panda_Appointment/panda-service-provider-appointment) |            约拍服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-appointment | :o:  |
| [panda-service-provider-appointment-type](https://gitee.com/Panda_Appointment/panda-service-provider-appointment-type) |          约拍类型服务提供者           | https://gitee.com/Panda_Appointment/panda-service-provider-appointment-type | :o:  |
| [panda-service-provider-works](https://gitee.com/Panda_Appointment/panda-service-provider-works) |            作品服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-works | :o:  |
| [panda-service-provider-order](https://gitee.com/Panda_Appointment/panda-service-provider-order) |            订单服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-order | :o:  |
| [panda-service-provider-spot](https://gitee.com/Panda_Appointment/panda-service-provider-spot) |           打卡点服务提供者            | https://gitee.com/Panda_Appointment/panda-service-provider-spot | :o:  |
| [panda-service-provider-quartz](https://gitee.com/Panda_Appointment/panda-service-provider-quartz) |          定时任务服务提供者           | https://gitee.com/Panda_Appointment/panda-service-provider-quartz | :o:  |
| [panda-service-provider-elasticsearch](https://gitee.com/Panda_Appointment/panda-service-provider-elasticsearch) |       elastic search服务提供者        | https://gitee.com/Panda_Appointment/panda-service-provider-elasticsearch | :o:  |
| [panda-service-sso](https://gitee.com/Panda_Appointment/panda-service-sso) |             单点登录服务              |    https://gitee.com/Panda_Appointment/panda-service-sso     | :o:  |
| [panda-service-consumer-user](https://gitee.com/Panda_Appointment/panda-service-consumer-user) |            服务消费者-用户            | https://gitee.com/Panda_Appointment/panda-service-consumer-user | :o:  |
| [panda-frontend](https://gitee.com/Panda_Appointment/panda-frontend) |            vue前端部署项目            |      https://gitee.com/Panda_Appointment/panda-frontend      | :o:  |
| [vue_panda_appointment](https://gitee.com/Panda_Appointment/vue_panda_appointment) |      熊猫约拍 - Vue前端代码仓库       |  https://gitee.com/Panda_Appointment/vue_panda_appointment   | :o:  |
| [panda-frontend-admin](https://gitee.com/Panda_Appointment/panda-frontend-admin) |         后台管理系统部署项目          |   https://gitee.com/Panda_Appointment/panda-frontend-admin   | :o:  |
| [vue_admin_panda_appointment](https://gitee.com/Panda_Appointment/vue_admin_panda_appointment) |    熊猫约拍 - vue后台管理代码仓库     | https://gitee.com/Panda_Appointment/vue_admin_panda_appointment | :o:  |



## 安装说明

### 网站

- 主地址：http://panda.alanlee.top
- 备用地址1：http://panda.nibuguai.cn

> 体验账号
>
> 帐号：test
>
> 密码：123456



### 微信公众号

![qrcode_for_gh_a80b923fbc86_258](https://alanlee-image-bed.oss-cn-shenzhen.aliyuncs.com/note_images/20200323125706-298071.jpeg)

### 微信小程序

审核未通过、请使用安卓app

![小程序](https://alanlee-image-bed.oss-cn-shenzhen.aliyuncs.com/note_images/20200323125826-678960.jpeg)

### 安卓 APP

下载地址：https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/package/panda-appointment.apk

![app](https://alanlee-image-bed.oss-cn-shenzhen.aliyuncs.com/note_images/20200323125827-616732.png)

> 体验账号
>
> 帐号：test
>
> 密码：123456



### 作品截图

#### 网站

> 主页

<img style="magin:10px; box-shadow: 2px 2px 10px #f1f1f1f1" src="https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/1%20-%20%E4%B8%BB%E9%A1%B5.png" />



> 约拍

![约拍](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/2%20-%20%E7%BA%A6%E6%8B%8D.png)



> 约拍详情页

![约拍详情页](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/2-1%20-%20%E7%BA%A6%E6%8B%8D%E8%AF%A6%E6%83%85.png)



> 作品

![作品](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/3%20-%20%E4%BD%9C%E5%93%81.png)



> 作品详情页

![作品详情页](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/3-1%20-%20%E4%BD%9C%E5%93%81%E8%AF%A6%E6%83%85.png)



> 打卡点

![打卡点](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/4%20-%20%E6%89%93%E5%8D%A1%E7%82%B9.png)



> 打卡点详情页

![打卡点详情页](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/4-1%20-%20%E6%89%93%E5%8D%A1%E7%82%B9%E8%AF%A6%E6%83%85%E9%A1%B5.png)



> 搜索

![搜索](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/5%20-%20%E6%90%9C%E7%B4%A2.png)



> 发布约拍

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/6%20-%20%E5%8F%91%E5%B8%83%E7%BA%A6%E6%8B%8D.png)



> 个人主页 - 我的约拍

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/7-1%20-%20%E4%B8%AA%E4%BA%BA%E4%B8%BB%E9%A1%B5%20-%20%E7%BA%A6%E6%8B%8D.png)



> 个人主页 - 我的作品

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/7-2%20-%20%E4%B8%AA%E4%BA%BA%E4%B8%BB%E9%A1%B5%20-%20%E4%BD%9C%E5%93%81.png)



> 个人主页 - 我的相册

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/7-3%20-%20%E4%B8%AA%E4%BA%BA%E4%B8%BB%E9%A1%B5%20-%20%E7%9B%B8%E5%86%8C.png)



> 个人主页 - 排期

![个人主页 - 排期](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/7-4%20-%20%20%E4%B8%AA%E4%BA%BA%E4%B8%BB%E9%A1%B5%20-%20%E6%8E%92%E6%9C%9F.png)



> 约拍类型

![约拍类型](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/8%20-%20%E7%BA%A6%E6%8B%8D%E7%B1%BB%E5%9E%8B.png)



> 注册

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/9%20-%20%E6%B3%A8%E5%86%8C.png)



> 登录

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/website/10%20-%20%E7%99%BB%E5%BD%95.png)



#### APP / 微信小程序

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/app/0%20-%20%E9%A1%B5%E9%9D%A2%E5%90%88%E9%9B%86.PNG)

#### 微信公众号

![微信公众号页面合集](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/wx-public-platform/%E5%BE%AE%E4%BF%A1%E5%85%AC%E4%BC%97%E5%8F%B7%E9%A1%B5%E9%9D%A2%E5%90%88%E9%9B%86.PNG)



#### 后台管理系统

![](https://alanlee-panda-appointment.oss-cn-shenzhen.aliyuncs.com/assert/images/back-manage-system/%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%E9%A1%B5%E9%9D%A2%E5%90%88%E9%9B%86.png)