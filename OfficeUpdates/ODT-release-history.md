---
title: Журнал выпусков средства развертывания Office (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Предоставляет ИТ-специалистам журнал выпусков средства развертывания Office (ODT)
ms.openlocfilehash: c01fbe403dacb0b474c37b7439eba5b616f8a08f
ms.sourcegitcommit: 591f5da255de896ef3156108349c6d2eaf34ed54
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/22/2020
ms.locfileid: "48174648"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="d344d-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="d344d-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="d344d-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, такие как приложения Microsoft 365, на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="d344d-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="d344d-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="d344d-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="d344d-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="d344d-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="d344d-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="d344d-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="d344d-108">**Поддерживаемые операционные системы**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="d344d-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="d344d-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="d344d-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="d344d-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="d344d-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="june-9-2020"></a><span data-ttu-id="d344d-111">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-111">June 9, 2020</span></span>

<span data-ttu-id="d344d-112">Версия 16.0.12827.20268 (setup.exe версии 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="d344d-112">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="d344d-113">Если канал не указан, в качестве текущего канала будет использоваться Актуальный канал.</span><span class="sxs-lookup"><span data-stu-id="d344d-113">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="d344d-114">Добавлена поддержка для Ежемесячного канала</span><span class="sxs-lookup"><span data-stu-id="d344d-114">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="d344d-115">Добавлена поддержка новых названий каналов</span><span class="sxs-lookup"><span data-stu-id="d344d-115">Added support for new channel names</span></span>
- <span data-ttu-id="d344d-116">Дополнительные функции устойчивости, позволяющие по возможности продолжать установку, даже если некоторые языковые ресурсы недоступны</span><span class="sxs-lookup"><span data-stu-id="d344d-116">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="d344d-117">Возможности MSIRemove, разворачиваемые для удаления продуктов Office 2007</span><span class="sxs-lookup"><span data-stu-id="d344d-117">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="d344d-118">Возможности MSIRemove, разворачиваемые для удаления ядра СУБД Access</span><span class="sxs-lookup"><span data-stu-id="d344d-118">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="d344d-119">15 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-119">April 15, 2020</span></span>

<span data-ttu-id="d344d-120">Версия 16.0.12624.20320 (setup.exe версии 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="d344d-120">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="d344d-121">Добавляет поддержку версий Office для Windows 7 с завершившимся сроком действия</span><span class="sxs-lookup"><span data-stu-id="d344d-121">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="d344d-122">Устраняет проблему, из-за которой параметры настройки могли применяться неправильно</span><span class="sxs-lookup"><span data-stu-id="d344d-122">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="d344d-123">Исправляет проблему, из-за которой неожиданно скачиваются CAT-файлы</span><span class="sxs-lookup"><span data-stu-id="d344d-123">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="d344d-124">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-124">January 16, 2020</span></span>

<span data-ttu-id="d344d-125">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="d344d-125">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="d344d-126">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="d344d-126">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="d344d-127">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="d344d-127">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="d344d-128">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345).</span><span class="sxs-lookup"><span data-stu-id="d344d-128">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="d344d-129">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-129">October 31, 2019</span></span>

<span data-ttu-id="d344d-130">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="d344d-130">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="d344d-131">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="d344d-131">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="d344d-132">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="d344d-132">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="d344d-133">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="d344d-133">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="d344d-134">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-134">July 10, 2019</span></span>

<span data-ttu-id="d344d-135">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="d344d-135">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="d344d-136">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="d344d-136">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="d344d-137">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="d344d-137">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="d344d-138">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-138">April 23, 2019</span></span>

<span data-ttu-id="d344d-139">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="d344d-139">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="d344d-140">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="d344d-140">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="d344d-141">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="d344d-141">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="d344d-142">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-142">April 16 2019</span></span>

<span data-ttu-id="d344d-143">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="d344d-143">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="d344d-144">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="d344d-144">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="d344d-145">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="d344d-145">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="d344d-146">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="d344d-146">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="d344d-147">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-147">March 13, 2019</span></span>

<span data-ttu-id="d344d-148">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="d344d-148">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="d344d-149">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="d344d-149">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="d344d-150">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="d344d-150">January 14, 2019</span></span>

<span data-ttu-id="d344d-151">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="d344d-151">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="d344d-152">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="d344d-152">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="d344d-153">См. также</span><span class="sxs-lookup"><span data-stu-id="d344d-153">Related links</span></span>

[<span data-ttu-id="d344d-154">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="d344d-154">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)