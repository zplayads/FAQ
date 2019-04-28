<!-- TOC -->

- [General](#general)
  - [How to deal with an error of DNS_PROBE_FINISHED_NXDOMAIN?](#how-to-deal-with-an-error-of-dnsprobefinishednxdomain)
  - [Do you support Report API?](#do-you-support-report-api)
  - [How do I find my Account ID and API Key?](#how-do-i-find-my-account-id-and-api-key)
- [User Acquisition](#user-acquisition)
  - [Why wasn't my campaign released?](#why-wasnt-my-campaign-released)
  - [What third-party tracking services do you support? Do you have in-house tracking tools?](#what-third-party-tracking-services-do-you-support-do-you-have-in-house-tracking-tools)
  - [What kinds of creatives do you support?](#what-kinds-of-creatives-do-you-support)
  - [Will it be available to send us the app name?](#will-it-be-available-to-send-us-the-app-name)
  - [What targeting options do you support?](#what-targeting-options-do-you-support)
- [Monetization](#monetization)
  - [Why can't I add adunits after adding apps?](#why-cant-i-add-adunits-after-adding-apps)
  - [Can the ad on my adunit be skipped?](#can-the-ad-on-my-adunit-be-skipped)
  - [Why don't I see any ads?](#why-dont-i-see-any-ads)
  - [Why can't I withdraw my earnings?](#why-cant-i-withdraw-my-earnings)

<!-- /TOC -->

If this document could not answer your question, you can contact us at service@atmosplay.com or creating issues in [issue page](https://github.com/zplayads/FAQ/issues) to describe your questions. We will help you solve your problem as soon as possible. 

## General
### How to deal with an error of DNS_PROBE_FINISHED_NXDOMAIN?
When encounter an error of DNS_PROBE_FINISHED_NXDOMAIN, please refer to this [doc](https://github.com/zplayads/FAQ/blob/master/edit_DNS.md);

### Do you support Report API?
We support Report API. 

If you are an advertiser, please refer to [Report API for Advertiser](https://github.com/zplayads/report_api/blob/master/Report%20API%20for%20Advertiser.md) to acquire your campaign data.

If you are a developer, please refer to [Report API for Developer](https://github.com/zplayads/report_api/blob/master/Report%20API%20for%20Developer.md) to acquire your monetization data.

### How do I find my Account ID and API Key?
You can find your Account ID and API Key in the "Account Information" page. If you are an advertiser, please click [here](https://buyers.zplayads.com/#/personalInfo/personalInfo/); If you are a developer, please click [here](https://sellers.zplayads.com/#/personal/personalInfo/);

![report_api](/img/report_api_en.png)

## User Acquisition
### Why wasn't my campaign released?
There are multiple reasons why we failed to release your campaign:
1. There is no balance left in the account. We require that you have a positive balance to release your campaign. If your balance is zero or negative, please recharge your account online or contact our operation support to recharge your account at service@atmosplay.com;
2. There is no approved creative under your campaign. Please check the status of the creatives under your campaign. If all creatives under your campaign are in paused or pending status, your campaign will not be released;
3. Your campaign is paused or expired. Please check the status of your campaign. 
    - If your campaign is paused, you can start it by clicking the "Start" button. If the campaign cannot be started, please check the app/creative status according to the message. If your campaign needs to be tested, please contact us at service@atmosplay.com;
    - If your campaign is expired, you need to add a new campaign for advertising;
4. Your app is not approved. Please check the status of the app. If the app is in pending or rejected status, the campaign under the app will not be released;

If your campaign is still not released, please contact us at service@atmosplay.com for help;

### What third-party tracking services do you support? Do you have in-house tracking tools?
For now, ZPLAY Ads support third-party tracking solutions including Appsflyer, Adjust, AdMaster, TalkingData, 热云, Singular, TUNE, 友盟, Kochava and Dataeye;

We also have in-house tracking tools. Please refer to the [Server-to-Server-Install-Tracking](https://github.com/zplayads/Help-Center-for-Promotion/blob/master/Tracking/ZPLAY%20Ads%20Advertiser%20Server%20to%20Server%20Install%20Tracking.md) doc for more details;

### What kinds of creatives do you support?
For now, ZPLAY Ads support playable creatives, H5 creatives, and video creatives;
1. Playable creatives: If you have requirements of making playable creatives, please contact us at service@atmosplay.com. We will make playable creatives for you;
2. H5 creatives: You can make H5 creatives according to [Specification for HTML Format Playable Ads](https://github.com/zplayads/specification-for-H5-playable-creative/blob/master/specification_for_html_format_playable_ads.md) and then upload your H5 creatives in ZPLAY Ads Advertiser Self-service System. Please click "ADD H5 CREATIVE" button in "AD CREATIVE" page to upload your H5 creatives;
3. Video creatives: You can click "ADD VIDEO CREATIVE" in "AD CREATIVE" page to upload your video creatives;
![add_creative_cn](/img/add_creative_en.png)

NOTE: About how to add creatives, please see [Guides about how to use ZPLAY Ads platform](https://github.com/zplayads/Help-Center-for-Promotion/blob/master/guides.md) for more details;

### Will it be available to send us the app name? 
We can’t send out app names. But we will be able to give you a unique identifier for the traffic, and through the identifier, you can compare the performance of your campaigns in different traffic sources. The table below lists the parameter of traffic app identifier in every third-party platforms:

|Third-party Platform Name|Parameter|
|-|-|
|Appsflyer|af_siteid|
|Adjust|adgroup|
|AdMaster|not supported for the moment|
|TalkingData|ad_unit_id|
|热云|subchannel|
|Singular|app_id|
|TUNE|sub_publisher|
|友盟|not supported for the moment|
|Kochava|site_id|
|Dataeye|not supported for the moment| 

### What targeting options do you support?

ZPLAY Ads provides a variety of targeting options including countries, period, network types, device types and OS versions. The table below lists detailed information on each option:

Target Options| Details
--|--
Countries|to cities for mainland China; to countries or regions outside of mainland China
Period|to specific hour(s)
Network Types|to 2G, 3G, and WiFi
Device Types|to phone and pad
OS Versions|to 5.x-9.x for Android campaign; to 9.x-12.x for iOS campaign

When creating or editing a campaign, you can set your target options in Targeting Settings;

## Monetization
### Why can't I add adunits after adding apps?
You can add adunits only after your app is approved. Please wait after your app is approved or contact at service@atmosplay.com to get help;

### Can the ad on my adunit be skipped?
1. If the type of your adunit is interstitial, then all ads display on this adunit can be skipped;
2. If the type of your adunit is rewarded video, then you can choose whether ads can be skipped on this adunit. Enter ZPLAY Ads [Developer Self-service System](https://sellers.zplayads.com/#/) and click "AdUnit Management" on the left to enter "[AdUnit Management](https://sellers.zplayads.com/#/ad/placeList/)" page. Click the "ADD NEW ADUNIT" button or "Edit" button to create or edit adunit. When the type of your ad unit is rewarded video, you can choose whether ads can be skipped on this adunit;
![skip](/img/skip_en.png)

### Why don't I see any ads?
You can check by following below steps:
1. If you are integrating ZPLAY Ads SDK, we recommend you use our test ID. There are adequate ads fill on test ID. Below is the test ID:

| OS| Ad Type | App_ID | Ad_Unit_ID |
| --- | --- | --- | --- |
| iOS     | Rewarded Video | A650AB0D-7BFC-2A81-3066-D3170947C3DA | BAE5DAAC-04A2-2591-D5B0-38FA846E45E7 |
| iOS     | Interstitial| A650AB0D-7BFC-2A81-3066-D3170947C3DA | 0868EBC0-7768-40CA-4226-F9924221C8EB |
| iOS     |Native Managed Rendering| A650AB0D-7BFC-2A81-3066-D3170947C3DA | DC9E199C-7C0B-FBFC-7E5A-26E7B5EE6BB3 |
| iOS     | Native Self Rendering | A650AB0D-7BFC-2A81-3066-D3170947C3DA | 25AED008-6B6F-BADB-F873-AE7CA61DFE98 |
|Android|Rewarded Video|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|3FBEFA05-3A8B-2122-24C7-A87D0BC9FEEC|
|Android|Interstitial|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|19393189-C4EB-3886-60B9-13B39407064E|
|Android| Native Managed Rendering|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|0246FB55-3042-9F29-D4AB-21C6349EEE83|
|Android|Native Self Rendering|5C5419C7-A2DE-88BC-A311-C3E7A646F6AF|BB8452AD-06E7-140B-00DC-FD6CB6B40FAA|

2. If you have integrated our SDK and launched your app successfully, please check the App ID and Ad Unit ID. You'll find the ID on the "[AdUnit Management](https://sellers.zplayads.com/#/ad/placeList/)" page;
3. If your App ID and Ad Unit ID are both right, please check the status of your app and ad unit;
4. If the status of your app and ad unit are both approved, please check the OS version of your device. We do not support very old os versions (iOS < 9.0 or Android < 4.0);
5. If you were still not able to get any ads, please contact us at service@atmosplay.com to get help;

### Why can't I withdraw my earnings?

If your "WITHDRAW" button is unable to click, please check:
1. Your current date. You can withdraw your earnings only from 00:00 15th to 24:00 20th (GMT+8:00) each month;
2. Your financial information. Only after you completing your financial information, you can withdraw your earnings. Please click the "ADD" button in "[Financial Information](https://sellers-test.zplayads.com/#/finance/financeEdit/)" page to fill your financial information;
3. Your unpaid earnings. If your settlement currency is RMB, you can withdraw your earnings only if your account has more than ￥1000 unpaid earnings; If your settlement currency is USD, you can withdraw your earnings only if your account has more than $250 unpaid earnings;

If you meet all the requirments above but still cannot click the "WITHDRAW" button, please contact us at service@atmosplay.com to get help;