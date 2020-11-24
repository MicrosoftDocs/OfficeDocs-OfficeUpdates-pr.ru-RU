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
ms.openlocfilehash: a1553a3f08a254c9c177fec88073073c34a3427c
ms.sourcegitcommit: 413694d561d367e93ad51c9be41495ad09a24af3
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/23/2020
ms.locfileid: "49385485"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="e1c72-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="e1c72-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="e1c72-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии "нажми и работай" Office, такие как Приложения Microsoft 365, на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="e1c72-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="e1c72-p101">Средство развертывания Office предоставляет дополнительные возможности управления установкой Office. Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление и нужно ли отображать интерфейс установки для пользователей. Дополнительные сведения о способе использования средства развертывания Office см. в статье [Общие сведения о средстве развертывания Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="e1c72-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="e1c72-108">**Поддерживаемые операционные системы**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="e1c72-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="e1c72-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="e1c72-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="e1c72-110">Скачать средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="e1c72-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-23-2020"></a><span data-ttu-id="e1c72-111">23 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-111">November 23, 2020</span></span>
<span data-ttu-id="e1c72-112">Версия 16.0.13328.20420 (setup.exe версии 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="e1c72-112">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="e1c72-113">Исправлена проблема, из-за которой средства проверки правописания не скачивались в режиме /download</span><span class="sxs-lookup"><span data-stu-id="e1c72-113">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="e1c72-114">Исправлена проблема, из-за которой возникал сбой режима /download при запуске в контексте непривилегированного пользователя</span><span class="sxs-lookup"><span data-stu-id="e1c72-114">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="e1c72-115">Исправлена проблема, из-за которой указание атрибута Version в XML-файле конфигурации приводило к неполному скачиванию в режиме /download</span><span class="sxs-lookup"><span data-stu-id="e1c72-115">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="e1c72-116">Исправлена проблема, из-за которой название средства развертывания Office отличалось от "setup.exe" при извлечении</span><span class="sxs-lookup"><span data-stu-id="e1c72-116">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="e1c72-117">Исправлена проблема, связанная с приоритетом источника установки при наличии в XML-файле конфигурации атрибута Channel.</span><span class="sxs-lookup"><span data-stu-id="e1c72-117">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="e1c72-118">10 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-118">November 10, 2020</span></span>
<span data-ttu-id="e1c72-119">Версия 16.0.13328.20356 (setupODT.exe версии 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="e1c72-119">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="e1c72-120">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="e1c72-120">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="e1c72-121">Чтобы избежать путаницы и легко диагностировать ошибки настройки, по умолчанию средство развертывания Office теперь называется setupODT.exe.</span><span class="sxs-lookup"><span data-stu-id="e1c72-121">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="e1c72-122">29 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-122">October 29, 2020</span></span>
<span data-ttu-id="e1c72-123">Версия 16.0.13328.20292 (setup.exe версии 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="e1c72-123">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="e1c72-124">Решает проблему, из-за которой определенные продукты Office 2007 могут неожиданно заблокировать установку при использовании RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="e1c72-124">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="e1c72-125">14 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-125">October 14, 2020</span></span>
<span data-ttu-id="e1c72-126">Версия 16.0.13231.20368 (setup.exe версии 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="e1c72-126">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="e1c72-127">Если канал не указан, по умолчанию для всех продуктов будет использоваться Ежемесячный канал.</span><span class="sxs-lookup"><span data-stu-id="e1c72-127">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="e1c72-128">Улучшена безопасность при запуске средства ODT из каталога, содержащего другие библиотеки DLL.</span><span class="sxs-lookup"><span data-stu-id="e1c72-128">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="e1c72-129">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="e1c72-129">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="e1c72-130">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-130">June 9, 2020</span></span>

<span data-ttu-id="e1c72-131">Версия 16.0.12827.20268 (setup.exe версии 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="e1c72-131">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="e1c72-132">Если канал не указан, в качестве текущего канала будет использоваться Актуальный канал.</span><span class="sxs-lookup"><span data-stu-id="e1c72-132">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="e1c72-133">Добавлена поддержка для Ежемесячного канала</span><span class="sxs-lookup"><span data-stu-id="e1c72-133">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="e1c72-134">Добавлена поддержка новых названий каналов</span><span class="sxs-lookup"><span data-stu-id="e1c72-134">Added support for new channel names</span></span>
- <span data-ttu-id="e1c72-135">Дополнительные функции устойчивости, позволяющие по возможности продолжать установку, даже если некоторые языковые ресурсы недоступны</span><span class="sxs-lookup"><span data-stu-id="e1c72-135">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="e1c72-136">Возможности MSIRemove, разворачиваемые для удаления продуктов Office 2007</span><span class="sxs-lookup"><span data-stu-id="e1c72-136">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="e1c72-137">Возможности MSIRemove, разворачиваемые для удаления ядра СУБД Access</span><span class="sxs-lookup"><span data-stu-id="e1c72-137">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="e1c72-138">15 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-138">April 15, 2020</span></span>

<span data-ttu-id="e1c72-139">Версия 16.0.12624.20320 (setup.exe версии 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="e1c72-139">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="e1c72-140">Добавляет поддержку версий Office для Windows 7 с завершившимся сроком действия</span><span class="sxs-lookup"><span data-stu-id="e1c72-140">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="e1c72-141">Устраняет проблему, из-за которой параметры настройки могли применяться неправильно</span><span class="sxs-lookup"><span data-stu-id="e1c72-141">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="e1c72-142">Исправляет проблему, из-за которой неожиданно скачиваются CAT-файлы</span><span class="sxs-lookup"><span data-stu-id="e1c72-142">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="e1c72-143">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-143">January 16, 2020</span></span>

<span data-ttu-id="e1c72-144">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="e1c72-144">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="e1c72-145">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="e1c72-145">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="e1c72-146">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="e1c72-146">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="e1c72-147">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345).</span><span class="sxs-lookup"><span data-stu-id="e1c72-147">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="e1c72-148">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-148">October 31, 2019</span></span>

<span data-ttu-id="e1c72-149">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="e1c72-149">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="e1c72-150">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="e1c72-150">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="e1c72-151">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="e1c72-151">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="e1c72-152">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="e1c72-152">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="e1c72-153">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-153">July 10, 2019</span></span>

<span data-ttu-id="e1c72-154">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="e1c72-154">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="e1c72-155">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="e1c72-155">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="e1c72-156">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="e1c72-156">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="e1c72-157">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-157">April 23, 2019</span></span>

<span data-ttu-id="e1c72-158">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="e1c72-158">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="e1c72-159">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="e1c72-159">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="e1c72-160">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="e1c72-160">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="e1c72-161">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-161">April 16 2019</span></span>

<span data-ttu-id="e1c72-162">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="e1c72-162">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="e1c72-163">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="e1c72-163">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="e1c72-164">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="e1c72-164">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="e1c72-165">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="e1c72-165">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="e1c72-166">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-166">March 13, 2019</span></span>

<span data-ttu-id="e1c72-167">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="e1c72-167">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="e1c72-168">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="e1c72-168">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="e1c72-169">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="e1c72-169">January 14, 2019</span></span>

<span data-ttu-id="e1c72-170">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="e1c72-170">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="e1c72-171">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="e1c72-171">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="e1c72-172">См. также</span><span class="sxs-lookup"><span data-stu-id="e1c72-172">Related links</span></span>

[<span data-ttu-id="e1c72-173">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="e1c72-173">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)