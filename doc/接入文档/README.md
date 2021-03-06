# BotSDK 接入文档

这个目录是Android APP接入BotSDK的全部文档，正式开发之前请通读文档。
**DBP升级，支持直接创建Android类型技能，文档中所有需要提交技能信息给到百度接口人的流程，现在可以直接忽略了**

## 基础概念

基础概念部分包含系统架构介绍，平台使用指南。文档中会介绍一些基础概念，这些基础概念可以帮助理解整个系统工作原理。
 - [DuerOS接入快速指南-App接入.pdf](DuerOS%E6%8E%A5%E5%85%A5%E5%BF%AB%E9%80%9F%E6%8C%87%E5%8D%97-App%E6%8E%A5%E5%85%A5.pdf)
 - [DBP平台使用指南.pdf](DBP%E5%B9%B3%E5%8F%B0%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97.pdf)

## APP Demo 快速入门

这一部分可以协助APP开发者快速跑起来一个demo，验证环境是否可用。
 - [BotSDK Demo开发指南.pdf](BotSDK%20Demo%E5%BC%80%E5%8F%91%E6%8C%87%E5%8D%97.pdf)

## 账户和支付

如果接入的APP需要使用百度账户登录，或者需要接入百度的支付流程，可以参考下面的文档
 - [BotSDK支付和授权流程接入文档.pdf](BotSDK%E6%94%AF%E4%BB%98%E5%92%8C%E6%8E%88%E6%9D%83%E6%B5%81%E7%A8%8B%E6%8E%A5%E5%85%A5%E6%96%87%E6%A1%A3.pdf)
对于APP端上收到的BotSDK支付结果通知，开发者需要到自己的后台服务器二次校验支付结果，以自己后台服务器返回的支付结果为准。支付校验参考文档：
 - [付款完成通知第三方接口 - AGroup –.pdf](%E4%BB%98%E6%AC%BE%E5%AE%8C%E6%88%90%E9%80%9A%E7%9F%A5%E7%AC%AC%E4%B8%89%E6%96%B9%E6%8E%A5%E5%8F%A3%20-%20AGroup%20%E2%80%93.pdf)

## 手机号一键授权功能接入
“手机号一键授权”指的是，三方技能请求度秘云端，小度设备可以弹出一个授权弹窗提示用户:"某某技能正在尝试获取设备登录的百度账户绑定的手机号......",用户确认授权之后，三方技能就可以拿到用户手机号。如果有获取用户手机号的需求，可以参考如下文档
 - [手机号一键授权接入文档](https://demo.codimd.org/s/B1DnQ4RuH)

## 技能外售卖功能接入
“技能外售卖”指的不用打开app，用户就可以在小度的其他销售渠道售卖app内的商品，例如小度app、小度在家设备端、双十一等运营活动。用户购买后打开商品对应的app后，app识别设备百度帐号下的售卖信息，并完成发货，用户即可享受商品权益。
如果有接入技能外售卖的需求，可以参考如下文档
 - [技能外售卖接入文档](https://demo.codimd.org/s/rJChB3AOH)

## H5应用接入DuerOS
H5应用接入DuerOS可以参考[H5-BotSDK](https://github.com/dueros/h5-bot-sdk)
