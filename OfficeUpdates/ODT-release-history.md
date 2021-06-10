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
ms.openlocfilehash: 163c358c39c4f1953a153ebc52bf909dedd49955
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/09/2021
ms.locfileid: "52851649"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="4858b-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="4858b-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="4858b-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, такие как приложения Microsoft 365, на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="4858b-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="4858b-p101">Средство развертывания Office предоставляет дополнительные возможности управления установкой Office. Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление и нужно ли отображать интерфейс установки для пользователей. Дополнительные сведения о способе использования средства развертывания Office см. в статье [Общие сведения о средстве развертывания Office](/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="4858b-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="4858b-108">**Поддерживаемые операционные системы**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="4858b-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="4858b-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="4858b-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="4858b-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="4858b-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="june-7-2021"></a><span data-ttu-id="4858b-111">7 июня 2021 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-111">June 7, 2021</span></span>
<span data-ttu-id="4858b-112">Версия 16.0.14026.20254 (версия файла setup.exe — 16.0.14026.20252)</span><span class="sxs-lookup"><span data-stu-id="4858b-112">Version 16.0.14026.20254 (setup.exe version 16.0.14026.20252)</span></span>
- <span data-ttu-id="4858b-113">Исправления для повышения надежности платформ ARM</span><span class="sxs-lookup"><span data-stu-id="4858b-113">Reliability fixes for ARM platforms</span></span>


## <a name="may-10-2021"></a><span data-ttu-id="4858b-114">10 мая 2021 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-114">May 10, 2021</span></span>
<span data-ttu-id="4858b-115">Версия 16.0.13929.20296 (версия файла setup.exe — 16.0.13929.20238)</span><span class="sxs-lookup"><span data-stu-id="4858b-115">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span></span>
- <span data-ttu-id="4858b-116">Устранена проблема, из-за которой в режиме /configure мог происходить сбой, если файл конфигурации содержит параметры MigrateArch и RemoveMSI.</span><span class="sxs-lookup"><span data-stu-id="4858b-116">Fixed an issue where /configure mode may fail if a configuration file includes both MigrateArch and RemoveMSI</span></span>
- <span data-ttu-id="4858b-117">Дополнительные улучшения для повышения надежности.</span><span class="sxs-lookup"><span data-stu-id="4858b-117">Additional reliability improvements</span></span>

## <a name="april-13-2021"></a><span data-ttu-id="4858b-118">13 апреля 2021 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-118">April 13, 2021</span></span>
<span data-ttu-id="4858b-119">Версия 16.0.13901.20336 (setup.exe версии 16.0.13901.20328)</span><span class="sxs-lookup"><span data-stu-id="4858b-119">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span></span>
- <span data-ttu-id="4858b-120">Исправления для повышения надежности для операций настройки, которые запускаются на устройствах с уже установленным Office.</span><span class="sxs-lookup"><span data-stu-id="4858b-120">Reliability fixes for configure operations that are run on devices with Office already installed</span></span>
- <span data-ttu-id="4858b-121">Исправления, позволяющие избежать дублирования диалогового окна хода выполнения в некоторых сценариях</span><span class="sxs-lookup"><span data-stu-id="4858b-121">Fixes to avoid showing duplicate progress UI in some scenarios</span></span>
- <span data-ttu-id="4858b-122">Улучшения точности кода ошибки, отображаемые в пользовательском интерфейсе</span><span class="sxs-lookup"><span data-stu-id="4858b-122">Improvements to error code accuracy shown in UI</span></span>
- <span data-ttu-id="4858b-123">Исправления для повышения надежности платформ ARM</span><span class="sxs-lookup"><span data-stu-id="4858b-123">Reliability fixes for ARM platforms</span></span>

## <a name="march-23-2021"></a><span data-ttu-id="4858b-124">23 марта 2021 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-124">March 23, 2021</span></span>
<span data-ttu-id="4858b-125">Версия 16.0.13801.20360 (setup.exe версии 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="4858b-125">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="4858b-126">Изменения для поддержки предстоящих выпусков продукта Office</span><span class="sxs-lookup"><span data-stu-id="4858b-126">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="4858b-127">Исправления для повышения надежности платформ ARM</span><span class="sxs-lookup"><span data-stu-id="4858b-127">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="4858b-128">25 февраля 2021 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-128">February 25, 2021</span></span>
<span data-ttu-id="4858b-129">Версия 16.0.13628.20476 (setup.exe версии 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="4858b-129">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="4858b-130">Исправлена проблема, из-за которой не проверялись файлы configuration.xml, указывающие несколько десятков языков</span><span class="sxs-lookup"><span data-stu-id="4858b-130">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="4858b-131">Исправлена проблема, из-за которой свойство FORCEAPPSHUTDOWN не учитывалось в сценариях MigrateArch</span><span class="sxs-lookup"><span data-stu-id="4858b-131">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="4858b-132">Исправлена проблема, из-за которой при указании 2 или более атрибутов PIDKEY в configuration.xml не удавалось установить PIDKeys</span><span class="sxs-lookup"><span data-stu-id="4858b-132">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="4858b-133">9 февраля 2021 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-133">February 9, 2021</span></span>
<span data-ttu-id="4858b-134">Версия 16.0.13628.20274 (setup.exe версии 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="4858b-134">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="4858b-135">Добавлена проверка для предупреждения о неподдерживаемых установках и их запрета в Windows 8.0</span><span class="sxs-lookup"><span data-stu-id="4858b-135">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="4858b-136">Исправления для повышения надежности устройств ARM64</span><span class="sxs-lookup"><span data-stu-id="4858b-136">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="4858b-137">12 января 2021 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-137">January 12, 2021</span></span>
<span data-ttu-id="4858b-138">Версия 16.0.13530.20376 (setup.exe версии 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="4858b-138">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="4858b-139">Исправлена проблема, из-за которой поврежденная или нестандартная регистрация продукта могла привести к сбою работы RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="4858b-139">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="4858b-140">Декабрь 21, 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-140">December 21, 2020</span></span>
<span data-ttu-id="4858b-141">Версия 16.0.13426.20370 (setup.exe версии 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="4858b-141">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="4858b-142">Исправлена проблема, из-за которой установка локального источника ProofingTools из канала PerpetualVL2019 завершалась сбоем</span><span class="sxs-lookup"><span data-stu-id="4858b-142">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="4858b-143">Исправлена проблема, чтобы удостовериться, что клиент технологии "Нажми и работай" предпринимает попытку самообновления при добавлении продуктов на языках без полноценной поддержки Office во время установки.</span><span class="sxs-lookup"><span data-stu-id="4858b-143">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="4858b-144">8 декабря 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-144">December 8, 2020</span></span>
<span data-ttu-id="4858b-145">Версия 16.0.13426.20308 (setup.exe версии 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="4858b-145">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="4858b-146">Устранена проблема, из-за которой режим скачивания блокировал загрузки канала Perpetual 2019, если на устройстве был установлен продукт Office из канала, отличающегося от Perpetual 2019.</span><span class="sxs-lookup"><span data-stu-id="4858b-146">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="4858b-147">Устранена проблема, из-за которой происходил сбой миграции архитектуры в локальном источнике, созданном с помощью режима загрузки, который указывал явную версию в XML-файле конфигурации.</span><span class="sxs-lookup"><span data-stu-id="4858b-147">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="4858b-148">23 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-148">November 23, 2020</span></span>
<span data-ttu-id="4858b-149">Версия 16.0.13328.20420 (setup.exe версии 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="4858b-149">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="4858b-150">Устранена проблема, из-за которой средства проверки правописания не скачивались в режиме /download</span><span class="sxs-lookup"><span data-stu-id="4858b-150">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="4858b-151">Устранена проблема, из-за которой возникал сбой режима /download при запуске в контексте непривилегированного пользователя</span><span class="sxs-lookup"><span data-stu-id="4858b-151">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="4858b-152">Устранена проблема, из-за которой указание атрибута Version в XML-файле конфигурации приводило к неполному скачиванию в режиме /download</span><span class="sxs-lookup"><span data-stu-id="4858b-152">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="4858b-153">Устранена проблема, из-за которой название средства развертывания Office отличалось от "setup.exe" при извлечении</span><span class="sxs-lookup"><span data-stu-id="4858b-153">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="4858b-154">Устранена проблема, связанная с приоритетом источника установки при наличии в XML-файле конфигурации атрибута Channel.</span><span class="sxs-lookup"><span data-stu-id="4858b-154">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="4858b-155">10 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-155">November 10, 2020</span></span>
<span data-ttu-id="4858b-156">Версия 16.0.13328.20356 (setupODT.exe версии 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="4858b-156">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="4858b-157">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="4858b-157">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="4858b-158">Чтобы избежать путаницы и легко диагностировать ошибки настройки, по умолчанию средство развертывания Office теперь называется setupODT.exe.</span><span class="sxs-lookup"><span data-stu-id="4858b-158">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="4858b-159">29 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-159">October 29, 2020</span></span>
<span data-ttu-id="4858b-160">Версия 16.0.13328.20292 (setup.exe версии 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="4858b-160">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="4858b-161">Решает проблему, из-за которой определенные продукты Office 2007 могут неожиданно заблокировать установку при использовании RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="4858b-161">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="4858b-162">14 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-162">October 14, 2020</span></span>
<span data-ttu-id="4858b-163">Версия 16.0.13231.20368 (setup.exe версии 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="4858b-163">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="4858b-164">Если канал не указан, по умолчанию для всех продуктов будет использоваться Ежемесячный канал.</span><span class="sxs-lookup"><span data-stu-id="4858b-164">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="4858b-165">Улучшена безопасность при запуске средства ODT из каталога, содержащего другие библиотеки DLL.</span><span class="sxs-lookup"><span data-stu-id="4858b-165">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="4858b-166">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="4858b-166">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="4858b-167">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-167">June 9, 2020</span></span>

<span data-ttu-id="4858b-168">Версия 16.0.12827.20268 (setup.exe версии 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="4858b-168">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="4858b-169">Если канал не указан, в качестве текущего канала будет использоваться Актуальный канал.</span><span class="sxs-lookup"><span data-stu-id="4858b-169">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="4858b-170">Добавлена поддержка для Ежемесячного канала</span><span class="sxs-lookup"><span data-stu-id="4858b-170">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="4858b-171">Добавлена поддержка новых названий каналов</span><span class="sxs-lookup"><span data-stu-id="4858b-171">Added support for new channel names</span></span>
- <span data-ttu-id="4858b-172">Дополнительные функции устойчивости, позволяющие по возможности продолжать установку, даже если некоторые языковые ресурсы недоступны</span><span class="sxs-lookup"><span data-stu-id="4858b-172">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="4858b-173">Возможности MSIRemove, разворачиваемые для удаления продуктов Office 2007</span><span class="sxs-lookup"><span data-stu-id="4858b-173">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="4858b-174">Возможности MSIRemove, разворачиваемые для удаления ядра СУБД Access</span><span class="sxs-lookup"><span data-stu-id="4858b-174">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="4858b-175">15 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-175">April 15, 2020</span></span>

<span data-ttu-id="4858b-176">Версия 16.0.12624.20320 (setup.exe версии 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="4858b-176">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="4858b-177">Добавляет поддержку версий Office для Windows 7 с завершившимся сроком действия</span><span class="sxs-lookup"><span data-stu-id="4858b-177">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="4858b-178">Устраняет проблему, из-за которой параметры настройки могли применяться неправильно</span><span class="sxs-lookup"><span data-stu-id="4858b-178">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="4858b-179">Исправляет проблему, из-за которой неожиданно скачиваются CAT-файлы</span><span class="sxs-lookup"><span data-stu-id="4858b-179">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="4858b-180">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-180">January 16, 2020</span></span>

<span data-ttu-id="4858b-181">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="4858b-181">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="4858b-182">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="4858b-182">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="4858b-183">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="4858b-183">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="4858b-184">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](/deployoffice/microsoft-search-bing).</span><span class="sxs-lookup"><span data-stu-id="4858b-184">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="4858b-185">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-185">October 31, 2019</span></span>

<span data-ttu-id="4858b-186">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="4858b-186">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="4858b-187">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="4858b-187">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="4858b-188">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="4858b-188">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="4858b-189">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="4858b-189">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="4858b-190">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-190">July 10, 2019</span></span>

<span data-ttu-id="4858b-191">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="4858b-191">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="4858b-192">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="4858b-192">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="4858b-193">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="4858b-193">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="4858b-194">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-194">April 23, 2019</span></span>

<span data-ttu-id="4858b-195">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="4858b-195">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="4858b-196">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="4858b-196">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="4858b-197">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="4858b-197">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="4858b-198">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-198">April 16 2019</span></span>

<span data-ttu-id="4858b-199">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="4858b-199">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="4858b-200">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="4858b-200">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="4858b-201">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="4858b-201">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="4858b-202">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="4858b-202">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="4858b-203">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-203">March 13, 2019</span></span>

<span data-ttu-id="4858b-204">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="4858b-204">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="4858b-205">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="4858b-205">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="4858b-206">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="4858b-206">January 14, 2019</span></span>

<span data-ttu-id="4858b-207">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="4858b-207">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="4858b-208">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="4858b-208">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="4858b-209">См. также</span><span class="sxs-lookup"><span data-stu-id="4858b-209">Related links</span></span>

[<span data-ttu-id="4858b-210">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="4858b-210">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)