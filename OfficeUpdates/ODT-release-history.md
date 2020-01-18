---
title: Журнал выпусков средства развертывания Office (ODT)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Предоставляет ИТ-специалистам журнал выпусков средства развертывания Office (ODT)
ms.openlocfilehash: fb59993362c4c186518f8472cb0330fa1b1e8d58
ms.sourcegitcommit: f042b25b15960fc4911a7e7d8500dcfd992ee95c
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/17/2020
ms.locfileid: "41230067"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="a133f-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="a133f-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="a133f-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, например, Office 365 профессиональный плюс на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="a133f-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="a133f-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="a133f-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="a133f-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="a133f-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="a133f-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="a133f-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="a133f-108">**Поддерживаемые операционные системы**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="a133f-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="a133f-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="a133f-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="a133f-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="a133f-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="january-16-2020"></a><span data-ttu-id="a133f-111">16 января 2020 г.</span><span class="sxs-lookup"><span data-stu-id="a133f-111">January 16, 2020</span></span>

<span data-ttu-id="a133f-112">Версия 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="a133f-112">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="a133f-113">Исправлена проблема, из-за которой в интерфейсе установки Office мог отображаться неправильный язык, если устанавливалось несколько языков</span><span class="sxs-lookup"><span data-stu-id="a133f-113">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="a133f-114">Исправлена проблема, из-за которой установка Office могла неожиданно завершаться сбоем, если устанавливались определенные пакеты средств проверки правописания</span><span class="sxs-lookup"><span data-stu-id="a133f-114">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="a133f-115">Добавлена поддержка дополнительного управления исходным развертыванием [функции Поиска (Майкрософт) в Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345).</span><span class="sxs-lookup"><span data-stu-id="a133f-115">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="a133f-116">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a133f-116">October 31, 2019</span></span>

<span data-ttu-id="a133f-117">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="a133f-117">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="a133f-118">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="a133f-118">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="a133f-119">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="a133f-119">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="a133f-120">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="a133f-120">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="a133f-121">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a133f-121">July 10, 2019</span></span>

<span data-ttu-id="a133f-122">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="a133f-122">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="a133f-123">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="a133f-123">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="a133f-124">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="a133f-124">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="a133f-125">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a133f-125">April 23, 2019</span></span>

<span data-ttu-id="a133f-126">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="a133f-126">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="a133f-127">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="a133f-127">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="a133f-128">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="a133f-128">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="a133f-129">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a133f-129">April 16 2019</span></span>

<span data-ttu-id="a133f-130">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="a133f-130">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="a133f-131">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="a133f-131">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="a133f-132">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="a133f-132">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="a133f-133">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="a133f-133">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="a133f-134">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a133f-134">March 13, 2019</span></span>

<span data-ttu-id="a133f-135">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="a133f-135">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="a133f-136">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="a133f-136">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="a133f-137">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a133f-137">January 14, 2019</span></span>

<span data-ttu-id="a133f-138">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="a133f-138">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="a133f-139">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="a133f-139">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="a133f-140">См. также</span><span class="sxs-lookup"><span data-stu-id="a133f-140">Related links</span></span>

[<span data-ttu-id="a133f-141">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="a133f-141">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)