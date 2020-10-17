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
ms.openlocfilehash: 4f65d41bfa18321a951fb18abcf919056bec7c5d
ms.sourcegitcommit: 57e715a8a3c0565b902cb3e6ca45d18a26f8ec45
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/15/2020
ms.locfileid: "48469998"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="5b6e2-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="5b6e2-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="5b6e2-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, такие как приложения Microsoft 365, на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="5b6e2-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="5b6e2-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="5b6e2-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="5b6e2-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="5b6e2-108">**Поддерживаемые операционные системы**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="5b6e2-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="5b6e2-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="5b6e2-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="5b6e2-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="5b6e2-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="october-14-2020"></a><span data-ttu-id="5b6e2-111">14 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-111">October 14, 2020</span></span>
<span data-ttu-id="5b6e2-112">Версия 16.0.13231.20368 (setup.exe версии 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="5b6e2-112">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="5b6e2-113">Если канал не указан, по умолчанию для всех продуктов будет использоваться Ежемесячный канал.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-113">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="5b6e2-114">Решает проблему, из-за которой определенные продукты Office 2007 могут неожиданно заблокировать установку при использовании RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="5b6e2-114">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>
- <span data-ttu-id="5b6e2-115">Улучшена безопасность при запуске средства ODT из каталога, содержащего другие библиотеки DLL.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-115">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="5b6e2-116">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="5b6e2-116">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="5b6e2-117">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-117">June 9, 2020</span></span>

<span data-ttu-id="5b6e2-118">Версия 16.0.12827.20268 (setup.exe версии 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="5b6e2-118">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="5b6e2-119">Если канал не указан, в качестве текущего канала будет использоваться Актуальный канал.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-119">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="5b6e2-120">Добавлена поддержка для Ежемесячного канала</span><span class="sxs-lookup"><span data-stu-id="5b6e2-120">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="5b6e2-121">Добавлена поддержка новых названий каналов</span><span class="sxs-lookup"><span data-stu-id="5b6e2-121">Added support for new channel names</span></span>
- <span data-ttu-id="5b6e2-122">Дополнительные функции устойчивости, позволяющие по возможности продолжать установку, даже если некоторые языковые ресурсы недоступны</span><span class="sxs-lookup"><span data-stu-id="5b6e2-122">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="5b6e2-123">Возможности MSIRemove, разворачиваемые для удаления продуктов Office 2007</span><span class="sxs-lookup"><span data-stu-id="5b6e2-123">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="5b6e2-124">Возможности MSIRemove, разворачиваемые для удаления ядра СУБД Access</span><span class="sxs-lookup"><span data-stu-id="5b6e2-124">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="5b6e2-125">15 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-125">April 15, 2020</span></span>

<span data-ttu-id="5b6e2-126">Версия 16.0.12624.20320 (setup.exe версии 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="5b6e2-126">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="5b6e2-127">Добавляет поддержку версий Office для Windows 7 с завершившимся сроком действия</span><span class="sxs-lookup"><span data-stu-id="5b6e2-127">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="5b6e2-128">Устраняет проблему, из-за которой параметры настройки могли применяться неправильно</span><span class="sxs-lookup"><span data-stu-id="5b6e2-128">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="5b6e2-129">Исправляет проблему, из-за которой неожиданно скачиваются CAT-файлы</span><span class="sxs-lookup"><span data-stu-id="5b6e2-129">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="5b6e2-130">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-130">January 16, 2020</span></span>

<span data-ttu-id="5b6e2-131">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="5b6e2-131">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="5b6e2-132">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="5b6e2-132">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="5b6e2-133">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="5b6e2-133">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="5b6e2-134">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345).</span><span class="sxs-lookup"><span data-stu-id="5b6e2-134">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="5b6e2-135">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-135">October 31, 2019</span></span>

<span data-ttu-id="5b6e2-136">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="5b6e2-136">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="5b6e2-137">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-137">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="5b6e2-138">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-138">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="5b6e2-139">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-139">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="5b6e2-140">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-140">July 10, 2019</span></span>

<span data-ttu-id="5b6e2-141">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="5b6e2-141">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="5b6e2-142">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-142">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="5b6e2-143">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-143">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="5b6e2-144">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-144">April 23, 2019</span></span>

<span data-ttu-id="5b6e2-145">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="5b6e2-145">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="5b6e2-146">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-146">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="5b6e2-147">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="5b6e2-147">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="5b6e2-148">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-148">April 16 2019</span></span>

<span data-ttu-id="5b6e2-149">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="5b6e2-149">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="5b6e2-150">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-150">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="5b6e2-151">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="5b6e2-151">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="5b6e2-152">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-152">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="5b6e2-153">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-153">March 13, 2019</span></span>

<span data-ttu-id="5b6e2-154">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="5b6e2-154">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="5b6e2-155">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-155">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="5b6e2-156">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-156">January 14, 2019</span></span>

<span data-ttu-id="5b6e2-157">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="5b6e2-157">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="5b6e2-158">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="5b6e2-158">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="5b6e2-159">См. также</span><span class="sxs-lookup"><span data-stu-id="5b6e2-159">Related links</span></span>

[<span data-ttu-id="5b6e2-160">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="5b6e2-160">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)