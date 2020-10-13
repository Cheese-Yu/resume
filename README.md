# 于海洋-前端开发-3年经验
于海洋 / 上海 / yhyclelo@sian.com / 南京林业大学-环境科学

## 技术栈
JavaScript | Node.js | Vue全家桶 | Weex | 小程序
  
## 个人经历
* **2013 ~ 2017 南京林业大学** 本科 环境科学
* **2017 ~ 2019  浙江善红信息技术有限公司**  
善红云金融SaaS管理后台，善红云智慧订单系统，智慧菜市场系统`(Vue2.x/Egg.js/MySQL/Redis/Socket.io/webpack/git)`
* **2019 ~ 至今  萤若(上海)互联网络科技有限公司**  
油罐go小程序(零售商城)、肌肤测试、AR试妆、数据管理后台、基于Weex开发App内嵌页、基于企业微信的CRM系统`(Vue2.x/Weex/Egg.js/MongoDB/小程序/webpack/git)`

  

## 项目经验
#### 小程序：油罐go
功能包括:注册、扫码加购、购物车、优惠券、支付、订单列表等。
* 小程序组件和方法封装
* 设计授权登录流程

#### Weex：基于Weex的开发
一些小样贩卖机、乳液机、货架交互屏等内的页面，包括:扫码关注、商品列表、商品详情、购物车、表单等。  
Weex各种组件的探索和封装、基于公司目前的App内嵌页资源管理模式，编写构建打包上传脚本。最初为手动打包通过后台上传素材，通过构建脚本可一键打包上传更新。  
* Weex组件和方法封装
* 公众号和后端对接
* 项目构建和管理优化
* APP问题排查
* 生成数据日报并邮件发送
* 技术栈: WebSocket/Node.js/MongoDB

#### PC：善红云智慧订单系统
订单管理，功能包括:登录、权限验证、订单查询及下载、个人/企业认证、设备增删改分组、日志等。  
负责MySQL库表设计，读写分离。使用Redis做任务队列/订阅广播(进程间通信)/加锁(防止抢单); socket.io与安卓App长连接通信，断开时发送邮件和短信告警; json2csv定时生成报表文件; 身份证识别Api对接。
* 使用Egg.js开发订单支付系统及后台管理相关接口
* 对接微信、支付宝支付
* 图片上传oss存储
* 任务队列管理，分组管理
* 通过Redis优化系统并发支持
* 组件封装
* 技术栈: Vue/Vuex/Egg.js/MySQL/Redis/Quasar/Socket.io


#### H5 / PC：智慧菜市场系统  
后台功能包括:广告增删改按区域发布，用户增删改激活，菜市场增删改，商品增删改，订单查询，流水趋势，操作日志等。  
微信H5功能包括:个人信息，设备绑定删除，菜品增删改，交易查询，流水趋势等。 
权限设计，交易系统设计，微信支付宝付款，微信公众号消息推送。
* 图片上传oss存储
* 银联商务支付对接
* 组件封装
* 使用ECharts绘制趋势图
* 技术栈：Egg.js/MySQL/Vue/Vuex/iView/ECharts

#### H5：AR试妆
内嵌在iOS中H5，功能包括：试妆、产品推荐、产品详情、拍照后扫码保存。  
* 设备配置、妆效与推荐产品关联设计
* 素材热更新
* 数据收集
* 组件封装
* 技术栈：Vue/Vuex/Socket.io

#### H5 / PC：肌肤测试及管理后台
后台采用Vue，服务端基于Egg.js，GraphQL，根据第三方返回的数据，商家可以通过后台定制推荐商品的规则。  
多品牌的肌肤测试，之前通过建立分支复制修改代码的方式，后迭代为通过读取数据库配置参数的方式，解决了重复开发和项目管理混乱的问题。  
* 公众号对接
* SVG绘制雷达图、环形进度条等
* 可配置的推荐逻辑和前端主题
* 技术栈: Vue/Vuex/Egg.js/SVG/GraphQL/MongoDB

  
## 其他
* Electron 可视化爬虫
* Tampermonkey脚本
