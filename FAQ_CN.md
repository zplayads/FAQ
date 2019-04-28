<!-- TOC -->

- [通用](#通用)
    - [遇到DNS解析错误如何处理？](#遇到dns解析错误如何处理)
    - [你们是否支持Report API？](#你们是否支持report-api)
    - [我从哪里可以获取Account ID和API Key？](#我从哪里可以获取account-id和api-key)
- [广告投放](#广告投放)
    - [为什么我的广告没有投放出去？](#为什么我的广告没有投放出去)
    - [你们的平台支持哪些三方监测？是否支持自有监测？](#你们的平台支持哪些三方监测是否支持自有监测)
    - [你们的平台支持什么类型的创意？](#你们的平台支持什么类型的创意)
    - [你们支持回传流量应用的名称吗？](#你们支持回传流量应用的名称吗)
    - [我可以从什么维度进行定向投放？](#我可以从什么维度进行定向投放)
- [流量变现](#流量变现)
    - [我已经创建好应用了，为什么无法创建广告位？](#我已经创建好应用了为什么无法创建广告位)
    - [广告位上投放的广告是否可跳过？](#广告位上投放的广告是否可跳过)
    - [为什么我看不到任何广告？](#为什么我看不到任何广告)
    - [为什么我无法提现？](#为什么我无法提现)

<!-- /TOC -->

如果本篇内容无法解答您的问题，您可以通过service@atmosplay.com联系我们或者在[issue页面](https://github.com/zplayads/FAQ/issues)创建issue来描述您遇到的问题，我们会尽快回复。

## 通用
### 遇到DNS解析错误如何处理？
当您遇到DNS解析错误的提示时，请参考[该文档](https://github.com/zplayads/FAQ/blob/master/%E4%BF%AE%E6%94%B9DNS.md)；

### 你们是否支持Report API？

我们支持Report API。
    
若您是广告主，可以参考我们的[广告主Report API文档](https://github.com/zplayads/report_api/blob/master/%E5%B9%BF%E5%91%8A%E4%B8%BBReport%20API.md)来获取您的投放数据；
   
若您是开发者，可以参考我们的[开发者Report API文档](https://github.com/zplayads/report_api/blob/master/%E5%BC%80%E5%8F%91%E8%80%85Report%20API.md)来获取您的变现数据；

### 我从哪里可以获取Account ID和API Key？
   
您可以在个人信息页面获取到您的Account ID和API Key，若您是广告主请[点击此处](https://buyers.zplayads.com/#/personalInfo/personalInfo/)，若您是开发者请[点击此处](https://sellers.zplayads.com/#/personal/personalInfo/)；

![report_api](/img/report_api.png)

## 广告投放
### 为什么我的广告没有投放出去？
广告没有投放出去可能有以下原因：
1. 您的账户余额为零或小于零；我们需要您账户里的余额大于零才可以投放，若您在首页的账户余额小于或等于零时，请进行在线充值或联系service@atmosplay.com以对您的账户进行充值；
2. 您的广告下没有状态为正常的素材；请检查该广告关联的素材的状态，若该广告下所有素材的状态为暂停或待审核，则您的广告无法被投放；
3. 您的广告投放状态为暂停或过期；请检查您的广告的状态，若广告投放状态为暂停或过期，则该广告无法被投放；暂停的广告，您可以手动开启，若无法开启，则根据页面提示检查应用或素材的状态，如果需要进行激活测试，请联系service@atmosplay.com；过期的广告无法再次投放，您需要新建广告进行投放；
4. 您的广告所属应用状态非正常；请检查您的广告所属的应用的状态，若应用状态为待审核或审核未通过，则该应用下的广告无法被展示；

若以上步骤检查后均无误后，广告还未投放出去，请联系service@atmosplay.com以获取帮助；

### 你们的平台支持哪些三方监测？是否支持自有监测？
目前，我们支持Appsflyer、Adjust、AdMaster、TalkingData、热云、Singular、TUNE，友盟，Kochava和Dataeye的三方监测；

同时，我们也支持广告主自有监测，请根据[接入文档](https://github.com/zplayads/Help-Center-for-Promotion/blob/master/Tracking/ZPLAYAds%E5%B9%BF%E5%91%8A%E4%B8%BB%E5%BA%94%E7%94%A8%E6%BF%80%E6%B4%BB%E5%9B%9E%E4%BC%A0%E6%8E%A5%E5%8F%A3.md)给ZPLAY Ads回传激活数据；

### 你们的平台支持什么类型的创意？
目前ZPLAY Ads支持可玩创意，H5创意和视频创意；
1. 可玩创意：若您有可玩创意制作需求，请与service@atmosplay.com联系，我们将为您制作可玩创意；
2. H5创意：您可以根据我们的[H5创意制作规范](https://github.com/zplayads/specification-for-H5-playable-creative)制作H5创意，制作完成后，在ZPLAY Ads广告主自助系统的广告创意页面点击“添加H5创意”，上传符合ZPLAY Ads规范的H5创意；
3. 视频创意：您可在ZPLAY Ads广告主自助系统中的广告创意页面选择“添加视频创意”，并根据要求上传视频创意；
![add_creative_cn](/img/add_creative_cn.png)

注：关于如何添加创意，请参考[ZPLAY Ads系统使用手册](https://github.com/zplayads/Help-Center-for-Promotion/blob/master/%E7%B3%BB%E7%BB%9F%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.md)；

### 你们支持回传流量应用的名称吗？
我们不支持直接回传流量应用名称，但是我们可以回传我们系统中应用唯一标识符，方便您查看您的广告在不同流量应用上的效果；下列表格列出了不同平台上，回传流量应用标识符的宏参数名称：

|三方平台 |宏参数名称|
|-|-|
|Appsflyer|af_siteid| 
|Adjust|adgroup| 
|AdMaster|暂不支持| 
|TalkingData|ad_unit_id| 
|热云|subchannel|
|Singular|app_id| 
|TUNE|sub_publisher| 
|友盟|暂不支持| 
|Kochava|site_id| 
|Dataeye|暂不支持| 

### 我可以从什么维度进行定向投放？
目前，ZPLAY Ads支持对地域、时段、网络模式、设备类型和操作系统版本进行定向投放；以下表格列出了每个维度下定向的具体内容：

维度|定向内容
--|--
地域|对于中国大陆，可定向到城市；对于中国大陆以外的国家或地区，可定向到该国家或地区
时段|可定向到指定的小时
网络模式|可定向到2G网络，3G网络，4G网络或WiFi
设备类型|可定向到手机或平板
系统版本|对于Android广告，我们支持定向5.x-9.x的系统版本；对于iOS广告，我们支持定向9.x-12.x的系统版本

您在创建或编辑广告时，可以在定向设置中对这些维度进行定向设置；


## 流量变现
### 我已经创建好应用了，为什么无法创建广告位？
应用审核通过后，才可以创建广告位。请等待应用通过审核或联系service@atmosplay.com获取帮助；

### 广告位上投放的广告是否可跳过？
1. 若广告位为插屏广告位，则在上面投放的广告均可跳过；
2. 若广告位为激励视频广告位，您可以在添加或编辑广告位页面，手动选择广告位上的广告是否可以跳过；您可以通过进入[ZPLAY Ads开发者自助系统](https://sellers.zplayads.com/#/)，点击左侧导航栏中的“广告位管理”，进入[广告位管理](https://sellers.zplayads.com/#/ad/placeList/)页面；点击“添加广告位”按钮，或在广告位列表点击“编辑”创建或编辑广告位，当广告形式为激励视频时，可以选择广告位是否可跳过；
![skip](/img/skip.png)

### 为什么我看不到任何广告？
您可先按照以下步骤检查：
1. 若您在接入或测试过程中，推荐使用我们的测试ID进行测试。测试ID上有充足的广告填充，测试ID如下：

| 操作系统 | 广告形式 | App_ID | Ad_Unit_ID |
| --- | --- | --- | --- |
| iOS     | 激励视频 | A650AB0D-7BFC-2A81-3066-D3170947C3DA | BAE5DAAC-04A2-2591-D5B0-38FA846E45E7 |
| iOS     | 插屏          | A650AB0D-7BFC-2A81-3066-D3170947C3DA | 0868EBC0-7768-40CA-4226-F9924221C8EB |
| iOS     | 原生托管渲染   | A650AB0D-7BFC-2A81-3066-D3170947C3DA | DC9E199C-7C0B-FBFC-7E5A-26E7B5EE6BB3 |
| iOS     | 原生自渲染     | A650AB0D-7BFC-2A81-3066-D3170947C3DA | 25AED008-6B6F-BADB-F873-AE7CA61DFE98 |
|Android|激励视频|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|3FBEFA05-3A8B-2122-24C7-A87D0BC9FEEC|
|Android|插屏|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|19393189-C4EB-3886-60B9-13B39407064E|
|Android|原生托管渲染|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|0246FB55-3042-9F29-D4AB-21C6349EEE83|
|Android|原生自渲染|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|BB8452AD-06E7-140B-00DC-FD6CB6B40FAA|

2. 若您已经接入成功并发布上线，请检查您的应用ID和广告位ID是否填写正确，您可以在[广告位列表页](https://sellers.zplayads.com/#/ad/placeList/)查看您的应用ID与广告位ID；
3. 若应用和广告位ID填写正确，请检查您的应用状态和广告位状态是否均为正常；
4. 若您的应用和广告位状态均为正常，请检查您所使用的设备操作系统版本，我们不支持在低于9.0的iOS操作系统版本及低于5.0的Android操作系统版本的设备上展示广告；
5. 若按以上步骤检查后均无问题，则有可能是您所在的国家或地区没有广告填充，请联系我们service@atmosplay.com以获取帮助；
   
### 为什么我无法提现？

如果您的提现按钮无法点击，请检查：
1. 您当前的日期。我们支持提现的日期是每个月的15日0点-20日24点（GMT+08:00），在此期间内，才可以提现；
2. 您的财务信息是否补充完整。只有财务信息填写完整时，才可以提现。请在[财务管理](https://sellers.zplayads.com/#/finance/financeList/)页面点击“添加”按钮以填写您的财务信息；
3. 您的可提现金额是否足够。当您使用人民币结算时，账户可提现金额需大于1000人民币才可提现；当您使用美元结算时，账户可提现金额需大于250美元才可提现；

如果上述条件都满足，您仍然无法提现，请联系service@atmosplay.com以获取帮助；
