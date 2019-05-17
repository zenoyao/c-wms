
### SaaS化的仓储管理

## 产品介绍
云擎WMS是一款针对中小仓库的SaaS化仓储管理系统，产品坚持系统指导人的思想，同时借助云计算及大数据的优势，致力于为客户提供轻量且高效的一体化仓储物流解决方案，系统同时支持B2B、B2C及O2O业务模式，含盖一般电商仓储、速递物流仓储、跨境电商仓储等多种业务形态。

## 技术框架
* .Net MVC 4.0
* MySQL 5.6
* Redis
* ActiveMQ

## 产品特色

* 性能参数：
    *  一套系统可以支持任意多个仓库；
    *  标准配置下，单服务器处理订单量1000单/秒。
    *  标准配置下，单仓日发货量30万单。
* 支持的业务形态：
    *  一般电商仓储
    *  速递物流仓储；
    *  跨境电商仓储；
* 支持的管理方式：
    *  无批次管理
    *  有批次管理（入库日期、生产日期、过期日期等）
    *  序列号管理
* 支持的作业方式：
    *  纸质拣货；
    *  电脑作业；
    *  手持作业；
    *  RFID作业；
    *  流水线作业；
    *  灯光作业；
    *  机器人作业；

![](http://c-scm.com/images/Feature.png)

## 系统组成

* Common：客户端与服务端公共组件，如基础数据对象、打印服务、数据安全等。
* Client：服务端公共组件，如数据库操作、会话处理、数据对象等。
* Server：服务端公共组件，如数据库操作、会话处理、数据对象等。
* WmsCommon：WMS客户端与服务端专用公共组件，如请求对象、会话管理等。
* WmsServer：WMS服务端专用公共组件，如数据库定义，数据持久化等。
* WmsDaemon：WMS守护进程，用于监视数据库、服务器状态，执行定时任务等。
* WmsWeb：WMS网页客户端，适用于管理人员。
* WmsEdi：WMS对外接口系统，适用于与外围各系统进行数据对接。
* WmsApp：WMS核心业务系统，服务于各种客户端。
* WinClient：WMS桌面客户端，适用于库内作业人员。
* AosClient：WMS安卓客户端，适用于库内作业人员。

## 产品演示

* [网页首页](http://c-scm.com/) 
* [演示账户](http://wms.c-scm.xyz/)

## 联系作者
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件：(avenyao#qq.com, 把#换成@)
* QQ群：297679499
* 微信：![](http://c-scm.com/images/wx_img.jpg)
