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
# <a name="default-ios-settings-in-express-configuration"></a><span data-ttu-id="1c101-103">默认快速配置中的 iOS 设置</span><span class="sxs-lookup"><span data-stu-id="1c101-103">Default iOS settings in Express Configuration</span></span>
<span data-ttu-id="1c101-104">快速配置预设与 iOS 设置建议，可帮助你快速设置的设备或用户组。</span><span class="sxs-lookup"><span data-stu-id="1c101-104">Express Configuration is preset with iOS setting suggestions to help you quickly set up a group of devices or users.</span></span> <span data-ttu-id="1c101-105">Intune for Education 选择是 Microsoft 建议和最佳学校环境的设置。</span><span class="sxs-lookup"><span data-stu-id="1c101-105">Intune for Education chooses settings that are both Microsoft-recommended and best for school environments.</span></span> <span data-ttu-id="1c101-106">进行更改以适合您的学校的规则和策略，或直接通过设置页以应用我们建议单击。</span><span class="sxs-lookup"><span data-stu-id="1c101-106">Make changes to fit your school's rules and policies, or click straight through the settings page to apply our recommendations.</span></span> 

<span data-ttu-id="1c101-107">有关设置和说明的完整列表，请参阅[Intune for Education 中的所有 iOS 设置](all-edu-settings-ios.md)。</span><span class="sxs-lookup"><span data-stu-id="1c101-107">For the complete list of settings and descriptions, see [All iOS settings in Intune for Education](all-edu-settings-ios.md).</span></span> 

> [!IMPORTANT]
> <span data-ttu-id="1c101-108">如果已禁用 iOS 配置，则在启动快速配置时，检查以确保设置了你的 MDM Apple Push certificate 和 DEP 令牌。</span><span class="sxs-lookup"><span data-stu-id="1c101-108">If iOS configurations are disabled when you launch Express Configuration, check to make sure you've set up both your MDM Apple Push certificate and DEP token.</span></span> <span data-ttu-id="1c101-109">如果您有这两项，请确保都已过期。</span><span class="sxs-lookup"><span data-stu-id="1c101-109">If you have both of these, make sure that neither has expired.</span></span> <span data-ttu-id="1c101-110">有关设置 iOS 设备管理的详细信息，请参阅[设置 iOS 设备管理](setup-ios-device-management.md)</span><span class="sxs-lookup"><span data-stu-id="1c101-110">For more information about setting up iOS device management, see [Set up iOS device management](setup-ios-device-management.md)</span></span>


## <a name="app-store-itunes-store-and-book-store"></a><span data-ttu-id="1c101-111">应用商店、 iTunes 应用商店和通讯簿应用商店</span><span class="sxs-lookup"><span data-stu-id="1c101-111">App Store, iTunes Store, and Book Store</span></span>  
<span data-ttu-id="1c101-112">设置</span><span class="sxs-lookup"><span data-stu-id="1c101-112">Setting</span></span>|<span data-ttu-id="1c101-113">建议的值</span><span class="sxs-lookup"><span data-stu-id="1c101-113">Suggested value</span></span>|  
|---|---|
|<span data-ttu-id="1c101-114">阻止 App Store</span><span class="sxs-lookup"><span data-stu-id="1c101-114">Block App Store</span></span>|<span data-ttu-id="1c101-115">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-115">Block</span></span>|
|<span data-ttu-id="1c101-116">块应用内购买</span><span class="sxs-lookup"><span data-stu-id="1c101-116">Block in-app purchases</span></span>|<span data-ttu-id="1c101-117">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-117">Block</span></span>|
|<span data-ttu-id="1c101-118">阻止应用商店和 iTunes 应用商店中的成人内容</span><span class="sxs-lookup"><span data-stu-id="1c101-118">Block explicit content in App Store and iTunes Store</span></span>|<span data-ttu-id="1c101-119">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-119">Block</span></span>|
|<span data-ttu-id="1c101-120">阻止下载标记为 erotica 的 Apple 丛书内容</span><span class="sxs-lookup"><span data-stu-id="1c101-120">Block downloading Apple Books content flagged as erotica</span></span>|<span data-ttu-id="1c101-121">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-121">Block</span></span>|  

## <a name="built-in-apps"></a><span data-ttu-id="1c101-122">内置应用</span><span class="sxs-lookup"><span data-stu-id="1c101-122">Built-in apps</span></span>  
<span data-ttu-id="1c101-123">设置</span><span class="sxs-lookup"><span data-stu-id="1c101-123">Setting</span></span>|<span data-ttu-id="1c101-124">建议的值</span><span class="sxs-lookup"><span data-stu-id="1c101-124">Suggested value</span></span>|  
|---|---|
|<span data-ttu-id="1c101-125">阻止使用相机</span><span class="sxs-lookup"><span data-stu-id="1c101-125">Block Camera</span></span>|<span data-ttu-id="1c101-126">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-126">Block</span></span>|
|<span data-ttu-id="1c101-127">阻止使用 FaceTime</span><span class="sxs-lookup"><span data-stu-id="1c101-127">Block FaceTime</span></span>|<span data-ttu-id="1c101-128">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-128">Block</span></span>|
|<span data-ttu-id="1c101-129">阻止 Game Center</span><span class="sxs-lookup"><span data-stu-id="1c101-129">Block Game Center</span></span>|<span data-ttu-id="1c101-130">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-130">Block</span></span>|  
|<span data-ttu-id="1c101-131">阻止 Apple 音乐</span><span class="sxs-lookup"><span data-stu-id="1c101-131">Block Apple Music</span></span>|<span data-ttu-id="1c101-132">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-132">Block</span></span>|
|<span data-ttu-id="1c101-133">块的消息应用程序</span><span class="sxs-lookup"><span data-stu-id="1c101-133">Block Messages app</span></span>|<span data-ttu-id="1c101-134">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-134">Block</span></span>|
|<span data-ttu-id="1c101-135">块 Apple 丛书</span><span class="sxs-lookup"><span data-stu-id="1c101-135">Block Apple Books</span></span>|<span data-ttu-id="1c101-136">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-136">Block</span></span>|  

## <a name="device-restrictions"></a><span data-ttu-id="1c101-137">设备限制</span><span class="sxs-lookup"><span data-stu-id="1c101-137">Device restrictions</span></span>  
<span data-ttu-id="1c101-138">设置名</span><span class="sxs-lookup"><span data-stu-id="1c101-138">Setting name</span></span>|<span data-ttu-id="1c101-139">建议的值</span><span class="sxs-lookup"><span data-stu-id="1c101-139">Suggested value</span></span>|
|---|---|
|<span data-ttu-id="1c101-140">阻止更改设备名</span><span class="sxs-lookup"><span data-stu-id="1c101-140">Block changing device name</span></span>|<span data-ttu-id="1c101-141">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-141">Block</span></span>|
|<span data-ttu-id="1c101-142">阻止更改墙纸</span><span class="sxs-lookup"><span data-stu-id="1c101-142">Block changing wallpaper</span></span>|<span data-ttu-id="1c101-143">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-143">Block</span></span>|
|<span data-ttu-id="1c101-144">阻止更改通知设置</span><span class="sxs-lookup"><span data-stu-id="1c101-144">Block changing notification settings</span></span>|<span data-ttu-id="1c101-145">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-145">Block</span></span>|
|<span data-ttu-id="1c101-146">阻止更改的内容和隐私限制</span><span class="sxs-lookup"><span data-stu-id="1c101-146">Block changes to content and privacy restrictions</span></span>|<span data-ttu-id="1c101-147">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-147">Block</span></span>|
|<span data-ttu-id="1c101-148">清除所有内容和设置的块按钮</span><span class="sxs-lookup"><span data-stu-id="1c101-148">Block button that erases all content and settings</span></span>|<span data-ttu-id="1c101-149">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-149">Block</span></span>|  

## <a name="icloud"></a><span data-ttu-id="1c101-150">iCloud</span><span class="sxs-lookup"><span data-stu-id="1c101-150">iCloud</span></span>
|<span data-ttu-id="1c101-151">设置</span><span class="sxs-lookup"><span data-stu-id="1c101-151">Setting</span></span>|<span data-ttu-id="1c101-152">建议的值</span><span class="sxs-lookup"><span data-stu-id="1c101-152">Suggested value</span></span>|
|---|---|
|<span data-ttu-id="1c101-153">阻止 iCloud 备份</span><span class="sxs-lookup"><span data-stu-id="1c101-153">Block iCloud backup</span></span>|<span data-ttu-id="1c101-154">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-154">Block</span></span>|
|<span data-ttu-id="1c101-155">阻止将文档同步到 iCloud</span><span class="sxs-lookup"><span data-stu-id="1c101-155">Block syncing documents to iCloud</span></span>|<span data-ttu-id="1c101-156">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-156">Block</span></span>|
|<span data-ttu-id="1c101-157">阻止 iCloud 照片库</span><span class="sxs-lookup"><span data-stu-id="1c101-157">Block iCloud Photo Library</span></span>|<span data-ttu-id="1c101-158">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-158">Block</span></span>|  

## <a name="lock-screen-and-wallpaper"></a><span data-ttu-id="1c101-159">锁定屏幕和墙纸</span><span class="sxs-lookup"><span data-stu-id="1c101-159">Lock screen and wallpaper</span></span>
<span data-ttu-id="1c101-160">设置</span><span class="sxs-lookup"><span data-stu-id="1c101-160">Setting</span></span>|<span data-ttu-id="1c101-161">建议的值</span><span class="sxs-lookup"><span data-stu-id="1c101-161">Suggested value</span></span>|
|---|---|
|<span data-ttu-id="1c101-162">阻止在锁屏界面上的通知</span><span class="sxs-lookup"><span data-stu-id="1c101-162">Block notifications on lock screen</span></span>|<span data-ttu-id="1c101-163">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-163">Block</span></span>|
|<span data-ttu-id="1c101-164">阻止从锁屏界面访问电子钱包</span><span class="sxs-lookup"><span data-stu-id="1c101-164">Block access to Wallet from lock screen</span></span>|<span data-ttu-id="1c101-165">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-165">Block</span></span>|
|<span data-ttu-id="1c101-166">设置设备锁定屏幕图像</span><span class="sxs-lookup"><span data-stu-id="1c101-166">Set device lock screen image</span></span>|<span data-ttu-id="1c101-167">.Jpg 或.png 文件;最大大小为 960 KB</span><span class="sxs-lookup"><span data-stu-id="1c101-167">A .jpg or .png file; maximum size 960 KB</span></span>|
|<span data-ttu-id="1c101-168">设置设备主屏幕图像</span><span class="sxs-lookup"><span data-stu-id="1c101-168">Set device home screen image</span></span>|<span data-ttu-id="1c101-169">.Jpg 或.png 文件;最大大小为 960 KB</span><span class="sxs-lookup"><span data-stu-id="1c101-169">A .jpg or .png file; maximum size 960 KB</span></span>|  

## <a name="passcode-touch-id-and-face-id"></a><span data-ttu-id="1c101-170">密码、 Touch ID 和人脸 ID</span><span class="sxs-lookup"><span data-stu-id="1c101-170">Passcode, Touch ID, and Face ID</span></span>  
<span data-ttu-id="1c101-171">设置</span><span class="sxs-lookup"><span data-stu-id="1c101-171">Setting</span></span>|<span data-ttu-id="1c101-172">建议的值</span><span class="sxs-lookup"><span data-stu-id="1c101-172">Suggested value</span></span>|
|---|---|  
|<span data-ttu-id="1c101-173">要求密码</span><span class="sxs-lookup"><span data-stu-id="1c101-173">Require passcode</span></span>|<span data-ttu-id="1c101-174">未配置</span><span class="sxs-lookup"><span data-stu-id="1c101-174">Not configured</span></span>|
|<span data-ttu-id="1c101-175">阻止更改密码</span><span class="sxs-lookup"><span data-stu-id="1c101-175">Block changing passcode</span></span>|<span data-ttu-id="1c101-176">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-176">Block</span></span>|
|<span data-ttu-id="1c101-177">擦除设备前的失败的密码尝试次数</span><span class="sxs-lookup"><span data-stu-id="1c101-177">Number of failed passcode attempts before wiping device</span></span>|<span data-ttu-id="1c101-178">未配置</span><span class="sxs-lookup"><span data-stu-id="1c101-178">Not configured</span></span>|
|<span data-ttu-id="1c101-179">块 Touch ID 和 Face ID</span><span class="sxs-lookup"><span data-stu-id="1c101-179">Block Touch ID and Face ID</span></span>|<span data-ttu-id="1c101-180">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-180">Block</span></span>|

## <a name="siri-and-search"></a><span data-ttu-id="1c101-181">使用 Siri 和搜索</span><span class="sxs-lookup"><span data-stu-id="1c101-181">Siri and search</span></span> 
<span data-ttu-id="1c101-182">设置</span><span class="sxs-lookup"><span data-stu-id="1c101-182">Setting</span></span>|<span data-ttu-id="1c101-183">建议的值</span><span class="sxs-lookup"><span data-stu-id="1c101-183">Suggested value</span></span>|
|---|---|   
|<span data-ttu-id="1c101-184">阻止使用 Siri</span><span class="sxs-lookup"><span data-stu-id="1c101-184">Block Siri</span></span>|<span data-ttu-id="1c101-185">阻止</span><span class="sxs-lookup"><span data-stu-id="1c101-185">Block</span></span>|  

## <a name="reset-default-settings"></a><span data-ttu-id="1c101-186">重置默认设置</span><span class="sxs-lookup"><span data-stu-id="1c101-186">Reset default settings</span></span>
<span data-ttu-id="1c101-187">若要将所有设置都还原为其默认值，请单击**重置为建议的默认设置**。</span><span class="sxs-lookup"><span data-stu-id="1c101-187">To restore all settings to their default values, click **Reset to suggested defaults**.</span></span> 

## <a name="next-steps"></a><span data-ttu-id="1c101-188">后续步骤</span><span class="sxs-lookup"><span data-stu-id="1c101-188">Next steps</span></span>  
<span data-ttu-id="1c101-189">全面了解组、 设置和监视 Intune for Education 中的冲突。</span><span class="sxs-lookup"><span data-stu-id="1c101-189">Learn all about groups, settings, and monitoring conflicts in Intune for Education.</span></span> 
* <span data-ttu-id="1c101-190">找出之间的差异[分配和动态](create-groups.md)组</span><span class="sxs-lookup"><span data-stu-id="1c101-190">Find out the difference between [assigned and dynamic](create-groups.md) groups</span></span>
* <span data-ttu-id="1c101-191">将分配[组管理员](group-admin-delegate.md)可帮助您管理您的学校内或跨地区的教室设置</span><span class="sxs-lookup"><span data-stu-id="1c101-191">Assign [group admins](group-admin-delegate.md) to help you manage classroom settings within your school or across the district</span></span>
* <span data-ttu-id="1c101-192">了解如何[设置继承](settings-inheritance.md)影响组分配</span><span class="sxs-lookup"><span data-stu-id="1c101-192">Learn how [settings inheritance](settings-inheritance.md) affects group assignments</span></span>
* <span data-ttu-id="1c101-193">审阅[报表](what-are-reports.md)地找出并解决设置冲突</span><span class="sxs-lookup"><span data-stu-id="1c101-193">Review [reports](what-are-reports.md) to pinpoint and troubleshoot setting conflicts</span></span>
