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
ms.openlocfilehash: 046054dfb781c3cd19ca6505e5ae5f2f362f6a86
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169967"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="a12c2-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="a12c2-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="a12c2-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, такие как приложения Microsoft 365, на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="a12c2-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="a12c2-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="a12c2-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="a12c2-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="a12c2-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="a12c2-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="a12c2-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="a12c2-108">**Поддерживаемые операционные системы**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="a12c2-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="a12c2-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="a12c2-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="a12c2-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="a12c2-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="march-23-2021"></a><span data-ttu-id="a12c2-111">23 марта 2021 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-111">March 23, 2021</span></span>
<span data-ttu-id="a12c2-112">Версия 16.0.13801.20360 (setup.exe версии 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="a12c2-112">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="a12c2-113">Изменения для поддержки предстоящих выпусков продукта Office</span><span class="sxs-lookup"><span data-stu-id="a12c2-113">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="a12c2-114">Исправления для повышения надежности платформ ARM</span><span class="sxs-lookup"><span data-stu-id="a12c2-114">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="a12c2-115">25 февраля 2021 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-115">February 25, 2021</span></span>
<span data-ttu-id="a12c2-116">Версия 16.0.13628.20476 (setup.exe версии 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="a12c2-116">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="a12c2-117">Исправлена проблема, из-за которой не проверялись файлы configuration.xml, указывающие несколько десятков языков</span><span class="sxs-lookup"><span data-stu-id="a12c2-117">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="a12c2-118">Исправлена проблема, из-за которой свойство FORCEAPPSHUTDOWN не учитывалось в сценариях MigrateArch</span><span class="sxs-lookup"><span data-stu-id="a12c2-118">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="a12c2-119">Исправлена проблема, из-за которой при указании 2 или более атрибутов PIDKEY в configuration.xml не удавалось установить PIDKeys</span><span class="sxs-lookup"><span data-stu-id="a12c2-119">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="a12c2-120">9 февраля 2021 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-120">February 9, 2021</span></span>
<span data-ttu-id="a12c2-121">Версия 16.0.13628.20274 (setup.exe версии 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="a12c2-121">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="a12c2-122">Добавлена проверка для предупреждения о неподдерживаемых установках и их запрета в Windows 8.0</span><span class="sxs-lookup"><span data-stu-id="a12c2-122">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="a12c2-123">Исправления для повышения надежности устройств ARM64</span><span class="sxs-lookup"><span data-stu-id="a12c2-123">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="a12c2-124">12 января 2021 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-124">January 12, 2021</span></span>
<span data-ttu-id="a12c2-125">Версия 16.0.13530.20376 (setup.exe версии 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="a12c2-125">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="a12c2-126">Исправлена проблема, из-за которой поврежденная или нестандартная регистрация продукта могла привести к сбою работы RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="a12c2-126">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="a12c2-127">Декабрь 21, 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-127">December 21, 2020</span></span>
<span data-ttu-id="a12c2-128">Версия 16.0.13426.20370 (setup.exe версии 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="a12c2-128">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="a12c2-129">Исправлена проблема, из-за которой установка локального источника ProofingTools из канала PerpetualVL2019 завершалась сбоем</span><span class="sxs-lookup"><span data-stu-id="a12c2-129">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="a12c2-130">Исправлена проблема, чтобы удостовериться, что клиент технологии "Нажми и работай" предпринимает попытку самообновления при добавлении продуктов на языках без полноценной поддержки Office во время установки.</span><span class="sxs-lookup"><span data-stu-id="a12c2-130">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="a12c2-131">8 декабря 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-131">December 8, 2020</span></span>
<span data-ttu-id="a12c2-132">Версия 16.0.13426.20308 (setup.exe версии 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="a12c2-132">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="a12c2-133">Устранена проблема, из-за которой режим скачивания блокировал загрузки канала Perpetual 2019, если на устройстве был установлен продукт Office из канала, отличающегося от Perpetual 2019.</span><span class="sxs-lookup"><span data-stu-id="a12c2-133">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="a12c2-134">Устранена проблема, из-за которой происходил сбой миграции архитектуры в локальном источнике, созданном с помощью режима загрузки, который указывал явную версию в XML-файле конфигурации.</span><span class="sxs-lookup"><span data-stu-id="a12c2-134">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="a12c2-135">23 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-135">November 23, 2020</span></span>
<span data-ttu-id="a12c2-136">Версия 16.0.13328.20420 (setup.exe версии 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="a12c2-136">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="a12c2-137">Устранена проблема, из-за которой средства проверки правописания не скачивались в режиме /download</span><span class="sxs-lookup"><span data-stu-id="a12c2-137">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="a12c2-138">Устранена проблема, из-за которой возникал сбой режима /download при запуске в контексте непривилегированного пользователя</span><span class="sxs-lookup"><span data-stu-id="a12c2-138">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="a12c2-139">Устранена проблема, из-за которой указание атрибута Version в XML-файле конфигурации приводило к неполному скачиванию в режиме /download</span><span class="sxs-lookup"><span data-stu-id="a12c2-139">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="a12c2-140">Устранена проблема, из-за которой название средства развертывания Office отличалось от "setup.exe" при извлечении</span><span class="sxs-lookup"><span data-stu-id="a12c2-140">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="a12c2-141">Устранена проблема, связанная с приоритетом источника установки при наличии в XML-файле конфигурации атрибута Channel.</span><span class="sxs-lookup"><span data-stu-id="a12c2-141">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="a12c2-142">10 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-142">November 10, 2020</span></span>
<span data-ttu-id="a12c2-143">Версия 16.0.13328.20356 (setupODT.exe версии 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="a12c2-143">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="a12c2-144">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="a12c2-144">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="a12c2-145">Чтобы избежать путаницы и легко диагностировать ошибки настройки, по умолчанию средство развертывания Office теперь называется setupODT.exe.</span><span class="sxs-lookup"><span data-stu-id="a12c2-145">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="a12c2-146">29 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-146">October 29, 2020</span></span>
<span data-ttu-id="a12c2-147">Версия 16.0.13328.20292 (setup.exe версии 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="a12c2-147">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="a12c2-148">Решает проблему, из-за которой определенные продукты Office 2007 могут неожиданно заблокировать установку при использовании RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="a12c2-148">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="a12c2-149">14 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-149">October 14, 2020</span></span>
<span data-ttu-id="a12c2-150">Версия 16.0.13231.20368 (setup.exe версии 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="a12c2-150">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="a12c2-151">Если канал не указан, по умолчанию для всех продуктов будет использоваться Ежемесячный канал.</span><span class="sxs-lookup"><span data-stu-id="a12c2-151">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="a12c2-152">Улучшена безопасность при запуске средства ODT из каталога, содержащего другие библиотеки DLL.</span><span class="sxs-lookup"><span data-stu-id="a12c2-152">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="a12c2-153">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="a12c2-153">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="a12c2-154">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-154">June 9, 2020</span></span>

<span data-ttu-id="a12c2-155">Версия 16.0.12827.20268 (setup.exe версии 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="a12c2-155">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="a12c2-156">Если канал не указан, в качестве текущего канала будет использоваться Актуальный канал.</span><span class="sxs-lookup"><span data-stu-id="a12c2-156">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="a12c2-157">Добавлена поддержка для Ежемесячного канала</span><span class="sxs-lookup"><span data-stu-id="a12c2-157">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="a12c2-158">Добавлена поддержка новых названий каналов</span><span class="sxs-lookup"><span data-stu-id="a12c2-158">Added support for new channel names</span></span>
- <span data-ttu-id="a12c2-159">Дополнительные функции устойчивости, позволяющие по возможности продолжать установку, даже если некоторые языковые ресурсы недоступны</span><span class="sxs-lookup"><span data-stu-id="a12c2-159">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="a12c2-160">Возможности MSIRemove, разворачиваемые для удаления продуктов Office 2007</span><span class="sxs-lookup"><span data-stu-id="a12c2-160">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="a12c2-161">Возможности MSIRemove, разворачиваемые для удаления ядра СУБД Access</span><span class="sxs-lookup"><span data-stu-id="a12c2-161">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="a12c2-162">15 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-162">April 15, 2020</span></span>

<span data-ttu-id="a12c2-163">Версия 16.0.12624.20320 (setup.exe версии 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="a12c2-163">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="a12c2-164">Добавляет поддержку версий Office для Windows 7 с завершившимся сроком действия</span><span class="sxs-lookup"><span data-stu-id="a12c2-164">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="a12c2-165">Устраняет проблему, из-за которой параметры настройки могли применяться неправильно</span><span class="sxs-lookup"><span data-stu-id="a12c2-165">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="a12c2-166">Исправляет проблему, из-за которой неожиданно скачиваются CAT-файлы</span><span class="sxs-lookup"><span data-stu-id="a12c2-166">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="a12c2-167">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-167">January 16, 2020</span></span>

<span data-ttu-id="a12c2-168">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="a12c2-168">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="a12c2-169">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="a12c2-169">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="a12c2-170">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="a12c2-170">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="a12c2-171">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](/deployoffice/microsoft-search-bing).</span><span class="sxs-lookup"><span data-stu-id="a12c2-171">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="a12c2-172">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-172">October 31, 2019</span></span>

<span data-ttu-id="a12c2-173">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="a12c2-173">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="a12c2-174">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="a12c2-174">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="a12c2-175">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="a12c2-175">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="a12c2-176">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="a12c2-176">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="a12c2-177">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-177">July 10, 2019</span></span>

<span data-ttu-id="a12c2-178">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="a12c2-178">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="a12c2-179">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="a12c2-179">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="a12c2-180">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="a12c2-180">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="a12c2-181">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-181">April 23, 2019</span></span>

<span data-ttu-id="a12c2-182">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="a12c2-182">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="a12c2-183">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="a12c2-183">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="a12c2-184">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="a12c2-184">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="a12c2-185">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-185">April 16 2019</span></span>

<span data-ttu-id="a12c2-186">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="a12c2-186">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="a12c2-187">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="a12c2-187">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="a12c2-188">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="a12c2-188">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="a12c2-189">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="a12c2-189">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="a12c2-190">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-190">March 13, 2019</span></span>

<span data-ttu-id="a12c2-191">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="a12c2-191">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="a12c2-192">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="a12c2-192">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="a12c2-193">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a12c2-193">January 14, 2019</span></span>

<span data-ttu-id="a12c2-194">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="a12c2-194">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="a12c2-195">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="a12c2-195">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="a12c2-196">См. также</span><span class="sxs-lookup"><span data-stu-id="a12c2-196">Related links</span></span>

[<span data-ttu-id="a12c2-197">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="a12c2-197">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)