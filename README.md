# hotpay
hotpay是微信和支付宝的个人免签，24小时全自动回调支付系统的php服务端程序，服务端和监控端全部开源

### hotpay：测试地址
 - 本项目已经部署到线下，可以点此在线测试：[点此获取最新版源码和教程](http://hotpay.jmkeji.net/) 
 
### hotpay：现有其它项目缺点
 - 1、大部分需要商家微信或支付宝才能实现全自动回调收款
 - 2、很多其它方案实现需要您事先提供很多张定额的二维码截图
 - 3、大部分其它方案是要收取价格很高的扣费率
 - 4、更有甚者很多其它方案，其实只是收款的通知系统而已，还需要手动确认，完全不能实现24小时全自动支付结算等处理
 - 5、有的其它方案金额不能固定，他们的实现方案需要价格有1分钱或几分钱的波动才能实现
 - 6、其它方案很多采用的是状态栏消息拦截方式，需要root。其实这些方案很不稳定
 
### hotpay：我的特点
 - 1、个人微信或支付宝都可接入本项目
 - 2、本系统服务端和监控端全部开源
 - 3、本系统能实现24小时全自动结算处理等操作，完全的零手工，常用场景为：自动充值、自动续费、自动发卡、自动XXX等业务
 - 4、支付的金额完全可自定义，而且金额没有一分钱的波动
 - 5、本系统采用底层HOOK技术，可以做到免root的HOOK方式，超稳定的实现24小时全自动支付结算功能
   
### hotpay：支持的二维码
 - 支付宝个人收款的推送通知
 - 支付宝商家二维码的收款推送通知
 - 支付宝店员通绑定的店员账号收款的推送通知 
 - 微信二维码收款推送通知
 - 微信店员收款推送通知
 - 微信收款商业版收款推送通知
 - 微信收款商业版店员到账收款通知

### hotpay：适用场景
 - 1、只要不违法的都可以！例如：
 - 2、自动充值，自动续费、自动发卡 
 - 3、收费展示、收费下载、收费通知系统 
 

### hotpay：源码下载
 - 源码下载地址：[点此获取最新版源码和教程](http://hotpay.jmkeji.net/) 
 - PHP服务端源码，安卓监控端，全部开源
 - 配备详细搭建文档和api文档
