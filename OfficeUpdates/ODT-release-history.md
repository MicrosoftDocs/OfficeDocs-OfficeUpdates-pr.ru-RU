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
ms.openlocfilehash: b9a5966e49653a4998a0cb3f3858decbe6f820c6
ms.sourcegitcommit: e7891ceed915afd2ae74689a366cebf9b3f60614
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/12/2021
ms.locfileid: "49837370"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="99f4f-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="99f4f-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="99f4f-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, такие как приложения Microsoft 365, на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="99f4f-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="99f4f-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="99f4f-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="99f4f-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="99f4f-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="99f4f-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="99f4f-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="99f4f-108">**Поддерживаемые операционные системы**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="99f4f-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="99f4f-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="99f4f-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="99f4f-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="99f4f-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="january-12-2021"></a><span data-ttu-id="99f4f-111">12 января 2021 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-111">January 12, 2021</span></span>
<span data-ttu-id="99f4f-112">Версия 16.0.13530.20376 (setup.exe версии 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="99f4f-112">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="99f4f-113">Исправлена проблема, из-за которой поврежденная или нестандартная регистрация продукта могла привести к сбою работы RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="99f4f-113">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="99f4f-114">Декабрь 21, 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-114">December 21, 2020</span></span>
<span data-ttu-id="99f4f-115">Версия 16.0.13426.20370 (setup.exe версии 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="99f4f-115">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="99f4f-116">Исправлена проблема, из-за которой установка локального источника ProofingTools из канала PerpetualVL2019 завершалась сбоем</span><span class="sxs-lookup"><span data-stu-id="99f4f-116">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="99f4f-117">Исправлена проблема, чтобы удостовериться, что клиент технологии "Нажми и работай" предпринимает попытку самообновления при добавлении продуктов на языках без полноценной поддержки Office во время установки.</span><span class="sxs-lookup"><span data-stu-id="99f4f-117">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="99f4f-118">8 декабря 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-118">December 8, 2020</span></span>
<span data-ttu-id="99f4f-119">Версия 16.0.13426.20308 (setup.exe версии 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="99f4f-119">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="99f4f-120">Устранена проблема, из-за которой режим скачивания блокировал загрузки канала Perpetual 2019, если на устройстве был установлен продукт Office из канала, отличающегося от Perpetual 2019.</span><span class="sxs-lookup"><span data-stu-id="99f4f-120">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="99f4f-121">Устранена проблема, из-за которой происходил сбой миграции архитектуры в локальном источнике, созданном с помощью режима загрузки, который указывал явную версию в XML-файле конфигурации.</span><span class="sxs-lookup"><span data-stu-id="99f4f-121">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="99f4f-122">23 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-122">November 23, 2020</span></span>
<span data-ttu-id="99f4f-123">Версия 16.0.13328.20420 (setup.exe версии 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="99f4f-123">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="99f4f-124">Устранена проблема, из-за которой средства проверки правописания не скачивались в режиме /download</span><span class="sxs-lookup"><span data-stu-id="99f4f-124">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="99f4f-125">Устранена проблема, из-за которой возникал сбой режима /download при запуске в контексте непривилегированного пользователя</span><span class="sxs-lookup"><span data-stu-id="99f4f-125">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="99f4f-126">Устранена проблема, из-за которой указание атрибута Version в XML-файле конфигурации приводило к неполному скачиванию в режиме /download</span><span class="sxs-lookup"><span data-stu-id="99f4f-126">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="99f4f-127">Устранена проблема, из-за которой название средства развертывания Office отличалось от "setup.exe" при извлечении</span><span class="sxs-lookup"><span data-stu-id="99f4f-127">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="99f4f-128">Устранена проблема, связанная с приоритетом источника установки при наличии в XML-файле конфигурации атрибута Channel.</span><span class="sxs-lookup"><span data-stu-id="99f4f-128">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="99f4f-129">10 ноября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-129">November 10, 2020</span></span>
<span data-ttu-id="99f4f-130">Версия 16.0.13328.20356 (setupODT.exe версии 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="99f4f-130">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="99f4f-131">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="99f4f-131">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="99f4f-132">Чтобы избежать путаницы и легко диагностировать ошибки настройки, по умолчанию средство развертывания Office теперь называется setupODT.exe.</span><span class="sxs-lookup"><span data-stu-id="99f4f-132">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="99f4f-133">29 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-133">October 29, 2020</span></span>
<span data-ttu-id="99f4f-134">Версия 16.0.13328.20292 (setup.exe версии 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="99f4f-134">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="99f4f-135">Решает проблему, из-за которой определенные продукты Office 2007 могут неожиданно заблокировать установку при использовании RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="99f4f-135">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="99f4f-136">14 октября 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-136">October 14, 2020</span></span>
<span data-ttu-id="99f4f-137">Версия 16.0.13231.20368 (setup.exe версии 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="99f4f-137">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="99f4f-138">Если канал не указан, по умолчанию для всех продуктов будет использоваться Ежемесячный канал.</span><span class="sxs-lookup"><span data-stu-id="99f4f-138">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="99f4f-139">Улучшена безопасность при запуске средства ODT из каталога, содержащего другие библиотеки DLL.</span><span class="sxs-lookup"><span data-stu-id="99f4f-139">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="99f4f-140">Повышение надежности и устойчивости</span><span class="sxs-lookup"><span data-stu-id="99f4f-140">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="99f4f-141">9 июня 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-141">June 9, 2020</span></span>

<span data-ttu-id="99f4f-142">Версия 16.0.12827.20268 (setup.exe версии 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="99f4f-142">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="99f4f-143">Если канал не указан, в качестве текущего канала будет использоваться Актуальный канал.</span><span class="sxs-lookup"><span data-stu-id="99f4f-143">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="99f4f-144">Добавлена поддержка для Ежемесячного канала</span><span class="sxs-lookup"><span data-stu-id="99f4f-144">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="99f4f-145">Добавлена поддержка новых названий каналов</span><span class="sxs-lookup"><span data-stu-id="99f4f-145">Added support for new channel names</span></span>
- <span data-ttu-id="99f4f-146">Дополнительные функции устойчивости, позволяющие по возможности продолжать установку, даже если некоторые языковые ресурсы недоступны</span><span class="sxs-lookup"><span data-stu-id="99f4f-146">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="99f4f-147">Возможности MSIRemove, разворачиваемые для удаления продуктов Office 2007</span><span class="sxs-lookup"><span data-stu-id="99f4f-147">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="99f4f-148">Возможности MSIRemove, разворачиваемые для удаления ядра СУБД Access</span><span class="sxs-lookup"><span data-stu-id="99f4f-148">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="99f4f-149">15 апреля 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-149">April 15, 2020</span></span>

<span data-ttu-id="99f4f-150">Версия 16.0.12624.20320 (setup.exe версии 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="99f4f-150">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="99f4f-151">Добавляет поддержку версий Office для Windows 7 с завершившимся сроком действия</span><span class="sxs-lookup"><span data-stu-id="99f4f-151">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="99f4f-152">Устраняет проблему, из-за которой параметры настройки могли применяться неправильно</span><span class="sxs-lookup"><span data-stu-id="99f4f-152">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="99f4f-153">Исправляет проблему, из-за которой неожиданно скачиваются CAT-файлы</span><span class="sxs-lookup"><span data-stu-id="99f4f-153">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="99f4f-154">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-154">January 16, 2020</span></span>

<span data-ttu-id="99f4f-155">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="99f4f-155">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="99f4f-156">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="99f4f-156">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="99f4f-157">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="99f4f-157">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="99f4f-158">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345).</span><span class="sxs-lookup"><span data-stu-id="99f4f-158">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="99f4f-159">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-159">October 31, 2019</span></span>

<span data-ttu-id="99f4f-160">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="99f4f-160">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="99f4f-161">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="99f4f-161">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="99f4f-162">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="99f4f-162">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="99f4f-163">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="99f4f-163">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="99f4f-164">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-164">July 10, 2019</span></span>

<span data-ttu-id="99f4f-165">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="99f4f-165">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="99f4f-166">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="99f4f-166">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="99f4f-167">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="99f4f-167">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="99f4f-168">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-168">April 23, 2019</span></span>

<span data-ttu-id="99f4f-169">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="99f4f-169">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="99f4f-170">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="99f4f-170">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="99f4f-171">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="99f4f-171">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="99f4f-172">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-172">April 16 2019</span></span>

<span data-ttu-id="99f4f-173">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="99f4f-173">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="99f4f-174">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="99f4f-174">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="99f4f-175">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="99f4f-175">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="99f4f-176">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="99f4f-176">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="99f4f-177">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-177">March 13, 2019</span></span>

<span data-ttu-id="99f4f-178">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="99f4f-178">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="99f4f-179">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="99f4f-179">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="99f4f-180">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="99f4f-180">January 14, 2019</span></span>

<span data-ttu-id="99f4f-181">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="99f4f-181">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="99f4f-182">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="99f4f-182">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="99f4f-183">См. также</span><span class="sxs-lookup"><span data-stu-id="99f4f-183">Related links</span></span>

[<span data-ttu-id="99f4f-184">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="99f4f-184">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)