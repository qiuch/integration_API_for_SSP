# 对接步骤

1. 提供准备接入的应用信息

    包括但不止于应用名称、包名、下载地址、广告位截图、广告位支持物料类型（jpg、jpeg、png、gif、html等）、是否支持多地址上报、是否存在预加载（影响请求成功到展示的数据对应关系）、是否支持 deeplink、是否可在应用内调用外部浏览器等，用于玉米交易平台的接入评估。

2. 获取账号，对接信息

    与玉米交易平台的商务人员沟通开始合作后，请在[https://www.yumimobi.com/cn/index.html](https://www.yumimobi.com/cn/index.html)页面点击“我是开发者”按钮进行注册，注册后请向玉米交易平台的商务人员提供注册的邮箱。在审核通过后，商务人员会提供给您SSP Token参数； APP ID,Slot ID等其他相关可直接在SSP前台页面获取。

3. 了解玉米交易平台对接文档

    + 熟悉玉米交易平台 [SSP对接文档协议](request_and_response.md) ，了解玉米交易平台基本的请求和返回参数，示例请参考 [广告请求和返回json示例](sample_of_request_and_response.md)

    + 确定对接的广告类型和每种广告对接的物料类型

4. 开发对接协议

    根据 [SSP对接文档协议](request_and_response.md) ，结合 [广告请求和返回json示例](sample_of_request_and_response.md) ，开始开发。开发完毕后，使用提供的测试Token及测试的APP ID、Slot ID进行测试，如果广告可以正常展示，则对接成功。
    > 测试Token为``EXVTAW2VYMKUY30TBGLUZ3XPC3H2YW6NQHPWBGF6LMNVBTA6LK9YNS6PMJAUNZG=`` 

     > 测试APP 参数：

<<<<<<< HEAD
=======

>>>>>>> 355abbb10a7bc94e6c2d6914505e89d469959d27
| OS | APP ID | Slot Format | Slot ID |
| ----- | ----- | ----- | ----- |
| Android | bg76gil7 | banner | an6o1ngv |
| Android | bg76gil7 | Interstitial | 13ohe4ze |
| Android | bg76gil7 | Reawrd Video | dsdibu5j |
| Android | bg76gil7 | Native | 13ur17b0 |
| Android | bg76gil7 | Splash | 50otuc9h |
| iOS | yywtptfq | banner | 5jr45zcy |
| iOS | yywtptfq | Interstitial | n0w2zkex |
| iOS | yywtptfq | Reawrd Video | hmtdjpt4 |
| iOS | yywtptfq | Native | gk8cmfh8 |
| iOS | yywtptfq | Splash | ss03ye17 |
<<<<<<< HEAD
=======

>>>>>>> 355abbb10a7bc94e6c2d6914505e89d469959d27

5. 小流量测试

    上述步骤完成后，进入小流量测试阶段。

    > 媒体放少量流量给到玉米交易平台，核对请求数、展示、点击等数据是否一致。具体小流量开启时间，请与玉米交易平台的商务人员确定。

6. 正式上线对接

    沟通确认没问题后，开始正式上线。
