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
ms.openlocfilehash: f578849552bb4fda0198bad3651170923d0ceb35
ms.sourcegitcommit: b19297da26ce6f740f3e2c94ea8a6c5d4e2aaa75
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/30/2020
ms.locfileid: "48806797"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="919b0-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="919b0-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="919b0-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, такие как приложения Microsoft 365, на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="919b0-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="919b0-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="919b0-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="919b0-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="919b0-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="919b0-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="919b0-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="919b0-108">**Поддерживаемые операционные системы** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="919b0-108">**Supported Operating System** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="919b0-109">**Инструкции по установке** : загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="919b0-109">**Install Instructions** : Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="919b0-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="919b0-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="october-29-2020"></a><span data-ttu-id="919b0-111">29 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-111">October 29, 2020</span></span>
<span data-ttu-id="919b0-112">Версия 16.0.13328.20292 (setup.exe версии 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="919b0-112">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="919b0-113">Решает проблему, из-за которой определенные продукты Office 2007 могут неожиданно заблокировать установку при использовании RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="919b0-113">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="919b0-114">14 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-114">October 14, 2020</span></span>
<span data-ttu-id="919b0-115">Версия 16.0.13231.20368 (setup.exe версии 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="919b0-115">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="919b0-116">Если канал не указан, по умолчанию для всех продуктов будет использоваться Ежемесячный канал.</span><span class="sxs-lookup"><span data-stu-id="919b0-116">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="919b0-117">Улучшена безопасность при запуске средства ODT из каталога, содержащего другие библиотеки DLL.</span><span class="sxs-lookup"><span data-stu-id="919b0-117">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="919b0-118">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="919b0-118">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="919b0-119">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-119">June 9, 2020</span></span>

<span data-ttu-id="919b0-120">Версия 16.0.12827.20268 (setup.exe версии 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="919b0-120">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="919b0-121">Если канал не указан, в качестве текущего канала будет использоваться Актуальный канал.</span><span class="sxs-lookup"><span data-stu-id="919b0-121">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="919b0-122">Добавлена поддержка для Ежемесячного канала</span><span class="sxs-lookup"><span data-stu-id="919b0-122">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="919b0-123">Добавлена поддержка новых названий каналов</span><span class="sxs-lookup"><span data-stu-id="919b0-123">Added support for new channel names</span></span>
- <span data-ttu-id="919b0-124">Дополнительные функции устойчивости, позволяющие по возможности продолжать установку, даже если некоторые языковые ресурсы недоступны</span><span class="sxs-lookup"><span data-stu-id="919b0-124">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="919b0-125">Возможности MSIRemove, разворачиваемые для удаления продуктов Office 2007</span><span class="sxs-lookup"><span data-stu-id="919b0-125">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="919b0-126">Возможности MSIRemove, разворачиваемые для удаления ядра СУБД Access</span><span class="sxs-lookup"><span data-stu-id="919b0-126">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="919b0-127">15 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-127">April 15, 2020</span></span>

<span data-ttu-id="919b0-128">Версия 16.0.12624.20320 (setup.exe версии 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="919b0-128">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="919b0-129">Добавляет поддержку версий Office для Windows 7 с завершившимся сроком действия</span><span class="sxs-lookup"><span data-stu-id="919b0-129">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="919b0-130">Устраняет проблему, из-за которой параметры настройки могли применяться неправильно</span><span class="sxs-lookup"><span data-stu-id="919b0-130">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="919b0-131">Исправляет проблему, из-за которой неожиданно скачиваются CAT-файлы</span><span class="sxs-lookup"><span data-stu-id="919b0-131">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="919b0-132">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-132">January 16, 2020</span></span>

<span data-ttu-id="919b0-133">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="919b0-133">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="919b0-134">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="919b0-134">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="919b0-135">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="919b0-135">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="919b0-136">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345).</span><span class="sxs-lookup"><span data-stu-id="919b0-136">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="919b0-137">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-137">October 31, 2019</span></span>

<span data-ttu-id="919b0-138">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="919b0-138">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="919b0-139">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="919b0-139">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="919b0-140">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="919b0-140">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="919b0-141">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="919b0-141">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="919b0-142">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-142">July 10, 2019</span></span>

<span data-ttu-id="919b0-143">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="919b0-143">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="919b0-144">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="919b0-144">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="919b0-145">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="919b0-145">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="919b0-146">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-146">April 23, 2019</span></span>

<span data-ttu-id="919b0-147">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="919b0-147">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="919b0-148">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="919b0-148">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="919b0-149">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="919b0-149">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="919b0-150">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-150">April 16 2019</span></span>

<span data-ttu-id="919b0-151">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="919b0-151">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="919b0-152">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="919b0-152">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="919b0-153">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="919b0-153">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="919b0-154">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="919b0-154">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="919b0-155">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-155">March 13, 2019</span></span>

<span data-ttu-id="919b0-156">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="919b0-156">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="919b0-157">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="919b0-157">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="919b0-158">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="919b0-158">January 14, 2019</span></span>

<span data-ttu-id="919b0-159">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="919b0-159">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="919b0-160">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="919b0-160">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="919b0-161">См. также</span><span class="sxs-lookup"><span data-stu-id="919b0-161">Related links</span></span>

[<span data-ttu-id="919b0-162">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="919b0-162">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)