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
ms.openlocfilehash: b0f53ad140880f7ef173efc544892d56f0658bb1
ms.sourcegitcommit: 917d87752cde322a74251b6d23b12815587d1e51
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/16/2019
ms.locfileid: "36444953"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="aef3e-103">Журнал выпусков средства развертывания Office</span><span class="sxs-lookup"><span data-stu-id="aef3e-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="aef3e-104">Средство развертывания Office (ODT) — это программа командной строки, которая позволяет скачать и развернуть версии “нажми и работай” Office, например, Office 365 профессиональный плюс на клиентских компьютерах.</span><span class="sxs-lookup"><span data-stu-id="aef3e-104">The Office 2016 Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Office 365 ProPlus to your client computers.</span></span> 


<span data-ttu-id="aef3e-105">ODT предоставляет более широкие возможности для контроля установки Office.</span><span class="sxs-lookup"><span data-stu-id="aef3e-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="aef3e-106">Вы можете указать, какие продукты и языковые версии устанавливать, как выполнять обновление, и нужно ли отображать интерфейс установки для пользователей.</span><span class="sxs-lookup"><span data-stu-id="aef3e-106">The ODT gives you more control over an Office installation: you can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="aef3e-107">Дополнительные сведения относительно использования ODT см. в [Обзоре средства развертывания Office](https://docs.microsoft.com/ru-RU/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="aef3e-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/en-us/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="aef3e-108">**Поддерживаемые операционные системы**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="aef3e-108">The tool runs on Windows 10 , Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, and Windows Server 2012 R2.</span></span> 
 
 <span data-ttu-id="aef3e-109">**Инструкции по установке**: загрузите и затем запустите самоизвлекающийся исполняемый файл, содержащий EXE-файл средства развертывания Office (setup.exe) и пример файла конфигурации (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="aef3e-109">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="aef3e-110">[Скачайте средство развертывания Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span><span class="sxs-lookup"><span data-stu-id="aef3e-110">Download the [Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="aef3e-111">10 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="aef3e-111">July 10, 2019</span></span>

<span data-ttu-id="aef3e-112">Версия 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="aef3e-112">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="aef3e-113">Добавлена поддержка дополнительных продуктов, устанавливаемых вместе с Office 2019: Access Runtime, Skype для бизнеса базовый.</span><span class="sxs-lookup"><span data-stu-id="aef3e-113">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="aef3e-114">Добавлена поддержка условной установки автономных продуктов при обновлении с MSI.</span><span class="sxs-lookup"><span data-stu-id="aef3e-114">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="aef3e-115">23 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="aef3e-115">April 23, 2019</span></span>

<span data-ttu-id="aef3e-116">Версия 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="aef3e-116">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="aef3e-117">Исправлена ошибка RemoveMSI=True для очистки связанных параметров реестра.</span><span class="sxs-lookup"><span data-stu-id="aef3e-117">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="aef3e-118">Обновлены коды ошибок для получения дополнительных сведениях о неожиданных сбоях (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="aef3e-118">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="aef3e-119">16 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="aef3e-119">April 16, 2019</span></span>

<span data-ttu-id="aef3e-120">Версия 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="aef3e-120">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="aef3e-121">Поддержка обновления 32-разрядной версии C2R до 64-разрядной версии C2R с новым атрибутом MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="aef3e-121">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="aef3e-122">Обновлена логика для /configure, которая позволяет получить доступ к конфигурации XML-файлов, хранящихся в веб-расположениях (http и https).</span><span class="sxs-lookup"><span data-stu-id="aef3e-122">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="aef3e-123">MatchInstalled добавлен в качестве нового атрибута, который позволяет ODT сопоставлять существующую версию при добавлении дополнительных продуктов или языков.</span><span class="sxs-lookup"><span data-stu-id="aef3e-123">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="aef3e-124">13 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="aef3e-124">March 13, 2019</span></span>

<span data-ttu-id="aef3e-125">Версия 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="aef3e-125">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="aef3e-126">Улучшены сценарии обновления и миграции.</span><span class="sxs-lookup"><span data-stu-id="aef3e-126">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="aef3e-127">14 января 2019 г.</span><span class="sxs-lookup"><span data-stu-id="aef3e-127">January 14, 2019</span></span>

<span data-ttu-id="aef3e-128">Версия 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="aef3e-128">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="aef3e-129">Улучшения ведения журнала и телеметрии для развертывания конфигурации.</span><span class="sxs-lookup"><span data-stu-id="aef3e-129">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="aef3e-130">Связанные ссылки</span><span class="sxs-lookup"><span data-stu-id="aef3e-130">Related links</span></span>

[<span data-ttu-id="aef3e-131">Примечания к выпуску ODT</span><span class="sxs-lookup"><span data-stu-id="aef3e-131">ODT Release notes</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)