---
title: 使用 Autopilot Reset 重新配置设备与 Intune for Education
titleSuffix: Intune for Education
description: 了解如何在 Intune for Education 中 Autopilot 重置。
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/17/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: ''
searchScope:
- IntuneEDU
ms.openlocfilehash: bfe0f385bdc66109fb189003e9a6cbaa894f1029
ms.sourcegitcommit: c85320170b0317de68be966581dd0e71d0cd58bd
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/18/2019
ms.locfileid: "68313994"
---
# <a name="autopilot-reset"></a><span data-ttu-id="3c74d-103">Autopilot 重置</span><span class="sxs-lookup"><span data-stu-id="3c74d-103">Autopilot Reset</span></span>
<span data-ttu-id="3c74d-104">你可以使用 Autopilot Reset 从设备中删除个人文件、应用和设置。</span><span class="sxs-lookup"><span data-stu-id="3c74d-104">You can use Autopilot Reset to remove personal files, apps, and settings from your devices.</span></span> <span data-ttu-id="3c74d-105">设备在 Intune 中保持注册状态, 并返回到完全配置或已知 IT 批准状态。</span><span class="sxs-lookup"><span data-stu-id="3c74d-105">The devices remain enrolled in Intune and are returned to a fully-configured or known IT-approved state.</span></span>
<span data-ttu-id="3c74d-106">可以通过 Intune for Education 门户 Autopilot 本地或远程重置设备。</span><span class="sxs-lookup"><span data-stu-id="3c74d-106">You can Autopilot Reset a device locally or remotely from the Intune for Education portal.</span></span>  

<span data-ttu-id="3c74d-107">使用 Intune for Education 门户, 无需 IT 人员访问每台设备即可启动该过程。</span><span class="sxs-lookup"><span data-stu-id="3c74d-107">Using the Intune for Education portal, you avoid the need for IT staff to visit each device to start the process.</span></span> <span data-ttu-id="3c74d-108">从门户中, 你可以重置单个设备, 或对组中的所有设备执行批量重置。</span><span class="sxs-lookup"><span data-stu-id="3c74d-108">From the portal, you can reset a single device or do a bulk reset for all devices in a group.</span></span> <span data-ttu-id="3c74d-109">通过重置组中的所有设备, 你可以快速擦除和重新配置学生设备, 以便为新的学年做好准备。</span><span class="sxs-lookup"><span data-stu-id="3c74d-109">Resetting all devices in a group lets you quickly wipe and reconfigure student devices to prepare them for the new school year.</span></span>  

<span data-ttu-id="3c74d-110">重置后, 原始设置会应用到设备, 然后与 Intune 同步以获取最新的策略。</span><span class="sxs-lookup"><span data-stu-id="3c74d-110">After a reset, the original settings are applied to the device and then it syncs with Intune to get the latest policies.</span></span> <span data-ttu-id="3c74d-111">在设备上使用 Autopilot 重置时, 将删除设备的主要用户。</span><span class="sxs-lookup"><span data-stu-id="3c74d-111">When Autopilot reset is used on a device, the device's primary user will be removed.</span></span> <span data-ttu-id="3c74d-112">重置之后登录的下一个用户将设置为主要用户。</span><span class="sxs-lookup"><span data-stu-id="3c74d-112">The next user who signs in after the reset will be set as the primary user.</span></span>   

## <a name="requirements"></a><span data-ttu-id="3c74d-113">要求</span><span class="sxs-lookup"><span data-stu-id="3c74d-113">Requirements</span></span>
<span data-ttu-id="3c74d-114">使用 Autopilot Reset 仅适用于运行 Windows 10 1709 版或更高版本的设备。</span><span class="sxs-lookup"><span data-stu-id="3c74d-114">Using Autopilot Reset locally is only available for devices running Windows 10 version 1709 or later.</span></span>
<span data-ttu-id="3c74d-115">仅适用于运行 Windows 10 版本17672或更高版本的设备进行远程使用 Autopilot 重置。</span><span class="sxs-lookup"><span data-stu-id="3c74d-115">Using Autopilot Reset remotely is only available for devices running Windows 10 build 17672 or later.</span></span>

## <a name="use-autopilot-reset-locally"></a><span data-ttu-id="3c74d-116">在本地使用 Autopilot 重置</span><span class="sxs-lookup"><span data-stu-id="3c74d-116">Use Autopilot Reset locally</span></span>
<span data-ttu-id="3c74d-117">如果需要擦除单个设备, 可以直接在设备上执行此操作。</span><span class="sxs-lookup"><span data-stu-id="3c74d-117">If you need to wipe a single device, you can do so directly on the device.</span></span> <span data-ttu-id="3c74d-118">在设备上, 按 CTRL + WIN + R。</span><span class="sxs-lookup"><span data-stu-id="3c74d-118">On the device, press CTRL+WIN+R.</span></span>  

## <a name="use-autopilot-reset-remotely-for-a-single-device"></a><span data-ttu-id="3c74d-119">对单个设备使用远程重置 Autopilot</span><span class="sxs-lookup"><span data-stu-id="3c74d-119">Use Autopilot Reset remotely for a single device</span></span>
1. <span data-ttu-id="3c74d-120">在 Intune for Education 中, 选择 "**组**" > 选择设备组。</span><span class="sxs-lookup"><span data-stu-id="3c74d-120">In Intune for Education, choose **Groups** > choose a device group.</span></span>
2. <span data-ttu-id="3c74d-121">选择 > Autopilot "**重置**的设备。</span><span class="sxs-lookup"><span data-stu-id="3c74d-121">Select a device > **Autopilot Reset**.</span></span> <span data-ttu-id="3c74d-122">若要确认重置, 请再次选择 " **Autopilot 重置**"。</span><span class="sxs-lookup"><span data-stu-id="3c74d-122">To confirm the reset, select **Autopilot Reset** again.</span></span>
2.  <span data-ttu-id="3c74d-123">启动重置时, 将显示一条消息。</span><span class="sxs-lookup"><span data-stu-id="3c74d-123">A message appears when the reset is initiated.</span></span> <span data-ttu-id="3c74d-124">设备会在下次连接到 Internet 时重置。</span><span class="sxs-lookup"><span data-stu-id="3c74d-124">The device will reset the next time it connects to the Internet.</span></span>  

## <a name="use-autopilot-reset-remotely-for-devices-in-bulk"></a><span data-ttu-id="3c74d-125">大容量地使用设备的 Autopilot 远程重置</span><span class="sxs-lookup"><span data-stu-id="3c74d-125">Use Autopilot Reset remotely for devices in bulk</span></span>  
1.  <span data-ttu-id="3c74d-126">在 Intune for Education 中, 选择 "**组**" > 选择组。</span><span class="sxs-lookup"><span data-stu-id="3c74d-126">In Intune for Education, choose **Groups** > choose the group.</span></span>
2. <span data-ttu-id="3c74d-127">选择**Autopilot "重置所有设备**"。</span><span class="sxs-lookup"><span data-stu-id="3c74d-127">Select **Autopilot Reset all devices**.</span></span>
2. <span data-ttu-id="3c74d-128">在 " **Autopilot 重置组**" 框中, 键入当前组的名称。</span><span class="sxs-lookup"><span data-stu-id="3c74d-128">In the **Autopilot Reset group** box, type the name of the current group.</span></span> <span data-ttu-id="3c74d-129">然后选择 " **Autopilot Reset** " 进行确认。</span><span class="sxs-lookup"><span data-stu-id="3c74d-129">Then select **Autopilot Reset** to confirm.</span></span>
3.  <span data-ttu-id="3c74d-130">每个设备将在下一次连接到 Internet 时进行重置。</span><span class="sxs-lookup"><span data-stu-id="3c74d-130">Each device will be reset the next time that it connects to the Internet.</span></span> <span data-ttu-id="3c74d-131">如果任何设备不支持远程 Autopilot 重置, 你将看到名为 "**设备无法重置**" 的表。</span><span class="sxs-lookup"><span data-stu-id="3c74d-131">If any of the devices don’t support remote Autopilot Reset, you'll see a table named **Devices failed to reset**.</span></span> <span data-ttu-id="3c74d-132">该表列出了每个设备以及无法重置的原因。</span><span class="sxs-lookup"><span data-stu-id="3c74d-132">The table lists each device and the reason that it couldn't be reset.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="3c74d-133">后续步骤</span><span class="sxs-lookup"><span data-stu-id="3c74d-133">Next steps</span></span>
[<span data-ttu-id="3c74d-134">通过远程操作管理设备</span><span class="sxs-lookup"><span data-stu-id="3c74d-134">Manage devices with remote actions</span></span>](edu-device-remote-actions.md)



