# 熊猫约拍

## 项目背景

随着电商时代的蓬勃发展，线上网店逐渐取代了线下实体店，许多平面模特为线上服装店拍摄服装照片，以便于买家判断是否需要购买此服装，但是电商要通过中间商才能找到自己想要的模特和摄影师，中间商利用信息不对等赚取差价，电商既没有少花钱，模特和摄影师也没有多赚钱，效率不高，价格却不低。

每年六月都是毕业季，许多学校都会有拍毕业照的需要，甚至有些人会需要摄影师跟拍他毕业时学校的场景，以此来记录自己在这所学校的青葱岁月，便于以后追忆自己的似水年华。

因为中西文化的逐渐融合，婚纱照成为现在每个新婚家庭必不可少的东西，但是照相馆里的婚纱照又贵，时间又很容易冲突，摄影师的水平也不一定符合要求。

艺术照成为许多人保留自己的美好时光的不二选择，但是要找到符合自己要求的摄影团队，时间不会冲突是很困难的。

摄影成为了不少人的兴趣爱好，但是作为一个摄影萌新，如何挑选相机和镜头呢？如何调焦？如何处理照片？如何根据不同的场景调试相机？

为了解决以上的问题和需求，我们创建了熊猫约拍。熊猫约拍致力于打造一个功能更加完善，效率更高的摄影约拍平台，让顾客和模特、摄影师可以直接对话，减少中间商赚差价，让模特和摄影师可以有更加高效的交流。让菜鸟摄影师从中学到摄影的技巧。熊猫约拍的web端与移动端并行，既可用电脑访问，也可以用手机app。



## 功能点

图示：已完成:o:、未开始:x:、开发中:computer:

### 用户功能

#### 核心功能

|      功能       | 描述 |   完成度   |
| :-------------: | :--: | :--------: |
|    预约拍照     |      |    :o:     |
|    发布预约     |      |    :o:     |
|    发布作品     |      |    :o:     |
|   打卡点推荐    |      | :computer: |
| 模特/摄影师推荐 |      | :computer: |
|   约拍排期表    |      |    :o:     |
|    短信通知     |      |    :x:     |
|    邮件通知     |      |    :x:     |
|    发布文章     |      |    :x:     |

#### 非核心功能

|      功能      |               描述               |   完成度   |
| :------------: | :------------------------------: | :--------: |
| 查询发布的约拍 |        查询自己发布的约拍        |    :o:     |
| 查询接单的约拍 |        查询自己接单的约拍        | :computer: |
|  修改约拍内容  |      修改自己发布的约拍内容      | :computer: |
|    删除约拍    |        删除自己发布的约拍        | :computer: |
|    查询作品    |        查询自己发布的作品        |    :o:     |
|    删除作品    |        删除自己发布的作品        | :computer: |
|  修改用户信息  | 修改头像、昵称、密码、身份信息等 | :computer: |



### 管理员功能

|     功能     |        描述        |   完成度   |
| :----------: | :----------------: | :--------: |
|   用户管理   |   对用户增删查改   | :computer: |
| 预约拍照管理 | 对预约拍照增删查改 | :computer: |
|   订单管理   |   对订单增删查改   | :computer: |
|   作品管理   |   对作品增删查改   | :computer: |
| 约拍类型管理 | 对约拍类型增删查改 | :computer: |
|  轮播图管理  |  对轮播图增删查改  | :computer: |
|  打卡点管理  |  对打卡点增删查改  |    :x:     |
| 统计用户城市 |    统计用户城市    | :computer: |
|   统计约拍   |      统计约拍      | :computer: |
|   统计作品   |      统计作品      | :computer: |



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
|           Zipkin           |       链路追踪        |   :o:    |
|            Zuul            |        API网关        |   :o:    |
|     Spring Boot Admin      |       服务监控        |   :x:    |
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
|           Quartz           |    分布式任务调度     |   :x:    |
|       Elastic Search       |    分布式全文搜索     |   :x:    |
|          RabbitMQ          |       消息队列        |   :x:    |
|          短信通知          |                       |   :x:    |
|          邮件发送          |                       |   :x:    |
|         支付宝支付         |                       |   :x:    |
|          微信登录          |                       |   :x:    |
|         微信公众号         |                       |   :x:    |

### 前端

|        技术        |           名称            |  集成状态  |
| :----------------: | :-----------------------: | :--------: |
|        HTML        |      超文本标记语言       |    :o:     |
|        CSS         |        层叠样式表         |    :o:     |
|     JavaScript     |       网页脚本语言        |    :o:     |
|       Vue.js       |         前端框架          |    :o:     |
|     VueRouter      |         前端路由          |    :o:     |
|        Vuex        |   状态管理（数据存储）    |    :o:     |
|     Element-UI     |       前端样式框架        |    :o:     |
|       Axios        |         网络请求          |    :o:     |
| vue-waterfall-easy |        瀑布流组件         |    :o:     |
|     vue2-admin     | 基于vue的后台管理前端框架 | :computer: |
|      echarts       |         图表框架          |    :o:     |
|      uni-app       |     移动端跨平台框架      | :computer: |

### 服务器

|       服务器       |     配置     |            使用            |
| :----------------: | :----------: | :------------------------: |
| 阿里云ECS - master | 2核4G 5M带宽 |         k8s主节点          |
| 阿里云ECS - node-1 | 1核2G 1M带宽 | 部署config、eureka、zuul等 |
|   百度智能云BCC    | 2核4G 1M带宽 |    部署微服务服务提供者    |
|     华为云ECS      | 1核2G 1M带宽 |    部署Nexus3 Maven私服    |
|     腾讯云ECS      | 1核2G 1M带宽 |    部署MySQL、Redis集群    |



## 软件架构

### 系统架构图

![image-20200310113200257](https://images.gitee.com/uploads/images/2020/0310/113729_a9e3ffb3_2231089.png)

### 部署架构图

![distributedSystem](https://images.gitee.com/uploads/images/2020/0310/113729_2c29a9dc_2231089.png)



## 项目链接

|                             名称                             |                 描述                  |                             链接                             | 公开 |
| :----------------------------------------------------------: | :-----------------------------------: | :----------------------------------------------------------: | :--: |
| [panda-files](https://gitee.com/Panda_Appointment/panda-files) | 存放文件docker-compose.yml和shell文件 |       https://gitee.com/Panda_Appointment/panda-files        | :o:  |
| [panda-config-repo](https://gitee.com/Panda_Appointment/panda-config-repo) |   分布式配置中心-存放配置文件的仓库   |    https://gitee.com/Panda_Appointment/panda-config-repo     | :x:  |
| [panda-dependencies](https://gitee.com/Panda_Appointment/panda-dependencies) |            统一的依赖管理             |    https://gitee.com/Panda_Appointment/panda-dependencies    | :x:  |
| [panda-domain](https://gitee.com/Panda_Appointment/panda-domain) |       统一的领域模型（实体类）        |       https://gitee.com/Panda_Appointment/panda-domain       | :x:  |
| [panda-config](https://gitee.com/Panda_Appointment/panda-config) |            分布式配置中心             |       https://gitee.com/Panda_Appointment/panda-config       | :x:  |
| [panda-eureka](https://gitee.com/Panda_Appointment/panda-eureka) |         分布式服务注册与发现          |       https://gitee.com/Panda_Appointment/panda-eureka       | :x:  |
| [panda-admin](https://gitee.com/Panda_Appointment/panda-admin) |          分布式应用管理中心           |       https://gitee.com/Panda_Appointment/panda-admin        | :x:  |
| [panda-zipkin](https://gitee.com/Panda_Appointment/panda-zipkin) |            分布式链路追踪             |       https://gitee.com/Panda_Appointment/panda-zipkin       | :x:  |
| [panda-gateway](https://gitee.com/Panda_Appointment/panda-gateway) |              分布式网关               |      https://gitee.com/Panda_Appointment/panda-gateway       | :x:  |
| [panda-common](https://gitee.com/Panda_Appointment/panda-common) |             通用项目模块              |       https://gitee.com/Panda_Appointment/panda-common       | :x:  |
| [panda-common-provider](https://gitee.com/Panda_Appointment/panda-common-provider) |           通用的服务提供者            |  https://gitee.com/Panda_Appointment/panda-common-provider   | :x:  |
| [panda-common-comsumer](https://gitee.com/Panda_Appointment/panda-common-comsumer) |           通用的服务消费者            |  https://gitee.com/Panda_Appointment/panda-common-comsumer   | :x:  |
| [panda-service-provider-user](https://gitee.com/Panda_Appointment/panda-service-provider-user) |            服务提供者-用户            | https://gitee.com/Panda_Appointment/panda-service-provider-user | :x:  |
| [panda-service-provider-image](https://gitee.com/Panda_Appointment/panda-service-provider-image) |            图片服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-image | :x:  |
| [panda-service-provider-carousel](https://gitee.com/Panda_Appointment/panda-service-provider-carousel) |           轮播图服务提供者            | https://gitee.com/Panda_Appointment/panda-service-provider-carousel | :x:  |
| [panda-service-provider-redis](https://gitee.com/Panda_Appointment/panda-service-provider-redis) |          缓存服务提供者redis          | https://gitee.com/Panda_Appointment/panda-service-provider-redis | :x:  |
| [panda-service-provider-appointment](https://gitee.com/Panda_Appointment/panda-service-provider-appointment) |            约拍服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-appointment | :x:  |
| [panda-service-provider-appointment-type](https://gitee.com/Panda_Appointment/panda-service-provider-appointment-type) |          约拍类型服务提供者           | https://gitee.com/Panda_Appointment/panda-service-provider-appointment-type | :x:  |
| [panda-service-provider-works](https://gitee.com/Panda_Appointment/panda-service-provider-works) |            作品服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-works | :x:  |
| [panda-service-provider-order](https://gitee.com/Panda_Appointment/panda-service-provider-order) |            订单服务提供者             | https://gitee.com/Panda_Appointment/panda-service-provider-order | :x:  |
| [panda-service-sso](https://gitee.com/Panda_Appointment/panda-service-sso) |             单点登录服务              |    https://gitee.com/Panda_Appointment/panda-service-sso     | :x:  |
| [panda-service-consumer-user](https://gitee.com/Panda_Appointment/panda-service-consumer-user) |            服务消费者-用户            | https://gitee.com/Panda_Appointment/panda-service-consumer-user | :x:  |

