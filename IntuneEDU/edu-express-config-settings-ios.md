---
title: 默认快速配置中的 iOS 设置
titleSuffix: Intune for Education
description: 列出了默认设置名称和设置在使用 Express 配置时的行为。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/19/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: af6eca94a4098885ef7c932f39e9c787e2a4450b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147485"
---
# <a name="default-ios-settings-in-express-configuration"></a>默认快速配置中的 iOS 设置
快速配置预设与 iOS 设置建议，可帮助你快速设置的设备或用户组。 Intune for Education 选择是 Microsoft 建议和最佳学校环境的设置。 进行更改以适合您的学校的规则和策略，或直接通过设置页以应用我们建议单击。 

有关设置和说明的完整列表，请参阅[Intune for Education 中的所有 iOS 设置](all-edu-settings-ios.md)。 

> [!IMPORTANT]
> 如果已禁用 iOS 配置，则在启动快速配置时，检查以确保设置了你的 MDM Apple Push certificate 和 DEP 令牌。 如果您有这两项，请确保都已过期。 有关设置 iOS 设备管理的详细信息，请参阅[设置 iOS 设备管理](setup-ios-device-management.md)


## <a name="app-store-itunes-store-and-book-store"></a>应用商店、 iTunes 应用商店和通讯簿应用商店  
设置|建议的值|  
|---|---|
|阻止 App Store|阻止|
|块应用内购买|阻止|
|阻止应用商店和 iTunes 应用商店中的成人内容|阻止|
|阻止下载标记为 erotica 的 Apple 丛书内容|阻止|  

## <a name="built-in-apps"></a>内置应用  
设置|建议的值|  
|---|---|
|阻止使用相机|阻止|
|阻止使用 FaceTime|阻止|
|阻止 Game Center|阻止|  
|阻止 Apple 音乐|阻止|
|块的消息应用程序|阻止|
|块 Apple 丛书|阻止|  

## <a name="device-restrictions"></a>设备限制  
设置名|建议的值|
|---|---|
|阻止更改设备名|阻止|
|阻止更改墙纸|阻止|
|阻止更改通知设置|阻止|
|阻止更改的内容和隐私限制|阻止|
|清除所有内容和设置的块按钮|阻止|  

## <a name="icloud"></a>iCloud
|设置|建议的值|
|---|---|
|阻止 iCloud 备份|阻止|
|阻止将文档同步到 iCloud|阻止|
|阻止 iCloud 照片库|阻止|  

## <a name="lock-screen-and-wallpaper"></a>锁定屏幕和墙纸
设置|建议的值|
|---|---|
|阻止在锁屏界面上的通知|阻止|
|阻止从锁屏界面访问电子钱包|阻止|
|设置设备锁定屏幕图像|.Jpg 或.png 文件;最大大小为 960 KB|
|设置设备主屏幕图像|.Jpg 或.png 文件;最大大小为 960 KB|  

## <a name="passcode-touch-id-and-face-id"></a>密码、 Touch ID 和人脸 ID  
设置|建议的值|
|---|---|  
|要求密码|未配置|
|阻止更改密码|阻止|
|擦除设备前的失败的密码尝试次数|未配置|
|块 Touch ID 和 Face ID|阻止|

## <a name="siri-and-search"></a>使用 Siri 和搜索 
设置|建议的值|
|---|---|   
|阻止使用 Siri|阻止|  

## <a name="reset-default-settings"></a>重置默认设置
若要将所有设置都还原为其默认值，请单击**重置为建议的默认设置**。 

## <a name="next-steps"></a>后续步骤  
全面了解组、 设置和监视 Intune for Education 中的冲突。 
* 找出之间的差异[分配和动态](create-groups.md)组
* 将分配[组管理员](group-admin-delegate.md)可帮助您管理您的学校内或跨地区的教室设置
* 了解如何[设置继承](settings-inheritance.md)影响组分配
* 审阅[报表](what-are-reports.md)地找出并解决设置冲突
