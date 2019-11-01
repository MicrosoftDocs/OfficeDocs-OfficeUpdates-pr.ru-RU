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
ms.openlocfilehash: 65dbad6110d38fd98fb7b6df94c2a54df2f89459
ms.sourcegitcommit: 6570d42ebb04c11b9aa40dac7825ae8da9694e10
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/31/2019
ms.locfileid: "37902405"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="f2233-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="f2233-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="f2233-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, например, Office 365 профессиональный плюс на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="f2233-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="f2233-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="f2233-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="f2233-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="f2233-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="f2233-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](https://docs.microsoft.com/ru-RU/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="f2233-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/ru-RU/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="f2233-108">**Поддерживаемые операционные системы**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="f2233-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="f2233-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="f2233-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="f2233-110">Скачайте средство развертывания Office</span><span class="sxs-lookup"><span data-stu-id="f2233-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="october-31-2019"></a><span data-ttu-id="f2233-111">31 октября 2019 г.</span><span class="sxs-lookup"><span data-stu-id="f2233-111">October 31, 2019</span></span>

<span data-ttu-id="f2233-112">Версия 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="f2233-112">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="f2233-113">Устранена проблема, не позволявшая установить Skype для бизнеса Basic 2019 с продуктами с бессрочной корпоративной лицензией 2019.</span><span class="sxs-lookup"><span data-stu-id="f2233-113">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="f2233-114">Устранена проблема, из-за которой в режиме скачивания ODT неожиданно происходил сбой в определенных обстоятельствах при использовании прокси.</span><span class="sxs-lookup"><span data-stu-id="f2233-114">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="f2233-115">Новая возможность, позволяющая в режиме скачивания ODT использовать HTTP-порт, отличный от порта 80.</span><span class="sxs-lookup"><span data-stu-id="f2233-115">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="f2233-116">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="f2233-116">July 10, 2019</span></span>

<span data-ttu-id="f2233-117">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="f2233-117">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="f2233-118">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="f2233-118">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="f2233-119">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="f2233-119">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="f2233-120">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="f2233-120">April 23, 2019</span></span>

<span data-ttu-id="f2233-121">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="f2233-121">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="f2233-122">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="f2233-122">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="f2233-123">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="f2233-123">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="f2233-124">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="f2233-124">April 16 2019</span></span>

<span data-ttu-id="f2233-125">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="f2233-125">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="f2233-126">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="f2233-126">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="f2233-127">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="f2233-127">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="f2233-128">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="f2233-128">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="f2233-129">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="f2233-129">March 13, 2019</span></span>

<span data-ttu-id="f2233-130">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="f2233-130">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="f2233-131">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="f2233-131">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="f2233-132">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="f2233-132">January 14, 2019</span></span>

<span data-ttu-id="f2233-133">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="f2233-133">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="f2233-134">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="f2233-134">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="f2233-135">См. также</span><span class="sxs-lookup"><span data-stu-id="f2233-135">Related links</span></span>

[<span data-ttu-id="f2233-136">Центр загрузки средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="f2233-136">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)