---
title: Заметки о выпуске для участников программы предварительной оценки Office
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
//: ''
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с ранним доступом последний список ключевых новых функций, исправлений или известных проблем
ms.openlocfilehash: 8cc5c8c9b11dabce030095a2d56404856850377a
ms.sourcegitcommit: d8ac84be012031d41fc29caf7e5b0bc32425a523
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/11/2019
ms.locfileid: "34857759"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="190c1-103">Заметки о выпуске для участников программы предварительной оценки Office</span><span class="sxs-lookup"><span data-stu-id="190c1-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="190c1-104">Эта статья содержит заметки о выпуске для сборок приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows, предоставляемых в рамках программы предварительной оценки.</span><span class="sxs-lookup"><span data-stu-id="190c1-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="190c1-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="190c1-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="190c1-106">Обратите внимание на то, что развертывание возможностей (а иногда даже исправлений) для участников программы предварительной оценки зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="190c1-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="190c1-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="190c1-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="190c1-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="190c1-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="190c1-109">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок</span><span class="sxs-lookup"><span data-stu-id="190c1-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="190c1-110">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки</span><span class="sxs-lookup"><span data-stu-id="190c1-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="190c1-111">Microsoft Teams для существующих установок Office 365 профессиональный плюс — с конца июня Microsoft Teams будет добавляться в существующие установки Office 365 профессиональный плюс (и Office 365 бизнес) при обновлении этих установок.</span><span class="sxs-lookup"><span data-stu-id="190c1-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="190c1-112">Дата добавления приложения Teams зависит от используемого канала обновления.</span><span class="sxs-lookup"><span data-stu-id="190c1-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="190c1-113">Дополнительные сведения см. в статье [Развертывание Microsoft Teams с Office 365 профессиональный плюс](https://docs.microsoft.com/ru-RU/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="190c1-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-7-2019"></a><span data-ttu-id="190c1-114">7 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-114">June 7, 2019</span></span>
<span data-ttu-id="190c1-115">Версия 1907 (сборка 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="190c1-115">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-116">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-116">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-117">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-117">Word</span></span> 
- <span data-ttu-id="190c1-118">Исправлена проблема, из-за которой возникал сбой в работе Word при автозамене первой буквы предложения на прописную</span><span class="sxs-lookup"><span data-stu-id="190c1-118">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="190c1-119">Улучшена производительность при редактировании документа в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="190c1-119">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="190c1-120">Исправлена проблема, из-за которой неправильно отображались векторные изображения, созданные в Adobe Illustrator</span><span class="sxs-lookup"><span data-stu-id="190c1-120">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-121">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-121">Excel</span></span>
- <span data-ttu-id="190c1-122">Исправлена проблема, из-за которой поля сортировки могли быть неправильно установлены при записи макроса</span><span class="sxs-lookup"><span data-stu-id="190c1-122">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="190c1-123">Исправлена проблема, приводящая к зависанию или сбою при пересчете формулы массива</span><span class="sxs-lookup"><span data-stu-id="190c1-123">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-124">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-124">PowerPoint</span></span>
- <span data-ttu-id="190c1-125">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-125">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-126">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-126">Outlook</span></span>
- <span data-ttu-id="190c1-127">Исправлена проблема, из-за которой встроенные вложения иногда имели неправильный масштаб</span><span class="sxs-lookup"><span data-stu-id="190c1-127">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="190c1-128">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-128">Access</span></span>
- <span data-ttu-id="190c1-129">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-129">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-130">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-130">Project</span></span>
- <span data-ttu-id="190c1-131">Исправлена проблема, из-за которой в расписании заданий с фиксированной длительностью может изменяться дата окончания</span><span class="sxs-lookup"><span data-stu-id="190c1-131">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="190c1-132">Исправлена проблема, из-за которой могло неправильно отображаться значение процента выполнения при открытии проекта из более ранней версии</span><span class="sxs-lookup"><span data-stu-id="190c1-132">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="190c1-133">31 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-133">May 31, 2019</span></span>
<span data-ttu-id="190c1-134">Версия 1906 (сборка 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="190c1-134">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-135">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-135">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-136">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-136">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="190c1-137">Диалоговое окно обращения в службу поддержки теперь закрепляется и отображается справа</span><span class="sxs-lookup"><span data-stu-id="190c1-137">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="190c1-138">Диалоговое окно, используемое для обращения в службу поддержки, отображается в области справа и выводится как закрепленное окно.</span><span class="sxs-lookup"><span data-stu-id="190c1-138">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="190c1-139">Рукописный ввод в вашем электронном письме!</span><span class="sxs-lookup"><span data-stu-id="190c1-139">Ink in Your Email!</span></span>

<span data-ttu-id="190c1-140">В сообщениях электронной почты Outlook теперь можно рисовать и создавать примечания к изображениям.</span><span class="sxs-lookup"><span data-stu-id="190c1-140">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="190c1-141">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-141">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="190c1-142">Открытие ссылок на документы в Word</span><span class="sxs-lookup"><span data-stu-id="190c1-142">Open document links in Word</span></span>

<span data-ttu-id="190c1-143">При переходе по ссылке на документ в Office вы можете изменить параметр, чтобы открывать его в приложении Word по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-143">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="190c1-144">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="190c1-144">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="190c1-145">Подробнее: https://support.office.com/ru-RU/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="190c1-145">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-146">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-146">Getting Started:</span></span>

<span data-ttu-id="190c1-147">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-147">Feature will default to off.</span></span> <span data-ttu-id="190c1-148">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="190c1-148">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="190c1-149">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-149">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="190c1-150">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="190c1-150">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="190c1-151">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="190c1-151">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="190c1-152">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="190c1-152">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-153">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-153">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-154">Чтобы запустить интерфейс согласия на открытие ссылки на документ Word, хранящийся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="190c1-154">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="190c1-155">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="190c1-155">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-156">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-156">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="190c1-157">Открытие ссылок на презентации в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-157">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="190c1-158">При переходе по ссылке на презентацию в Office вы можете изменить параметр, чтобы открывать ее в приложении PowerPoint по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-158">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="190c1-159">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="190c1-159">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="190c1-160">Подробнее: https://support.office.com/ru-RU/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="190c1-160">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-161">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-161">Getting Started:</span></span>

<span data-ttu-id="190c1-162">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-162">Feature will default to off.</span></span> <span data-ttu-id="190c1-163">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="190c1-163">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="190c1-164">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-164">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="190c1-165">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="190c1-165">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="190c1-166">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="190c1-166">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="190c1-167">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="190c1-167">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-168">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-168">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-169">Чтобы запустить интерфейс согласия на открытие ссылки на презентацию PowerPoint, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="190c1-169">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="190c1-170">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="190c1-170">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-171">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-171">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="190c1-172">Открытие ссылок на книги в Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-172">Open workbook links in Excel</span></span>

<span data-ttu-id="190c1-173">При переходе по ссылке на книгу в Office вы можете изменить параметр, чтобы открывать ее в приложении Excel по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-173">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="190c1-174">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="190c1-174">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="190c1-175">Подробнее: https://support.office.com/ru-RU/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="190c1-175">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-176">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-176">Getting Started:</span></span>

<span data-ttu-id="190c1-177">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-177">Feature will default to off.</span></span> <span data-ttu-id="190c1-178">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="190c1-178">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="190c1-179">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="190c1-179">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="190c1-180">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="190c1-180">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="190c1-181">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="190c1-181">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="190c1-182">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="190c1-182">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-183">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-183">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-184">Чтобы запустить интерфейс согласия на открытие ссылки на книгу Excel, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="190c1-184">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="190c1-185">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="190c1-185">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-186">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-186">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="190c1-187">Все</span><span class="sxs-lookup"><span data-stu-id="190c1-187">All</span></span>
- <span data-ttu-id="190c1-188">Исправлена проблема, из-за которой файлы иногда автоматически сохранялись даже при отключенной функции автоматического сохранения.</span><span class="sxs-lookup"><span data-stu-id="190c1-188">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="190c1-189">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-189">Word</span></span> 
- <span data-ttu-id="190c1-190">Исправлена ошибка, которая могла не позволять некоторым пользователям сохранять файлы в SharePoint</span><span class="sxs-lookup"><span data-stu-id="190c1-190">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-191">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-191">Excel</span></span>
- <span data-ttu-id="190c1-192">Исправлена проблема с возможным отображением неправильного значка для неактивных фильтров</span><span class="sxs-lookup"><span data-stu-id="190c1-192">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-193">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-193">PowerPoint</span></span>
- <span data-ttu-id="190c1-194">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-194">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-195">Outlook</span></span>
- <span data-ttu-id="190c1-196">Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span><span class="sxs-lookup"><span data-stu-id="190c1-196">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="190c1-197">Исправлена проблема, не позволявшая функции безопасных ссылок анализировать URL-адрес с конечным пробелом</span><span class="sxs-lookup"><span data-stu-id="190c1-197">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="190c1-198">Устранена проблема, из-за которой помещения отображались доступными за пределами нерабочего времени</span><span class="sxs-lookup"><span data-stu-id="190c1-198">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="190c1-199">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-199">Access</span></span>
- <span data-ttu-id="190c1-200">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-200">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-201">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-201">Project</span></span>
- <span data-ttu-id="190c1-202">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-202">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="190c1-203">24 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-203">May 24, 2019</span></span>
<span data-ttu-id="190c1-204">Версия 1906 (сборка 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="190c1-204">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-205">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-205">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="190c1-206">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="190c1-206">User Experience Updates</span></span>

<span data-ttu-id="190c1-207">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="190c1-207">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-208">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-208">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="190c1-209">Все</span><span class="sxs-lookup"><span data-stu-id="190c1-209">All</span></span>

- <span data-ttu-id="190c1-210">Исправлена проблема, из-за которой не отображалась область чата</span><span class="sxs-lookup"><span data-stu-id="190c1-210">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="190c1-211">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-211">Word</span></span> 
- <span data-ttu-id="190c1-212">Исправлена проблема, из-за которой в некоторых случаях приложение Word могло неправильно выделять текст на наличие грамматических ошибок</span><span class="sxs-lookup"><span data-stu-id="190c1-212">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-213">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-213">Excel</span></span>
- <span data-ttu-id="190c1-214">Исправлена проблема, из-за которой применялся неправильный значок для элементов диаграммы</span><span class="sxs-lookup"><span data-stu-id="190c1-214">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="190c1-215">Исправлена проблема, приводившая к активации неверной книги в скрипте VBA, если эта книга уже открыта</span><span class="sxs-lookup"><span data-stu-id="190c1-215">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-216">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-216">PowerPoint</span></span>
- <span data-ttu-id="190c1-217">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-217">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-218">Outlook</span></span>
- <span data-ttu-id="190c1-219">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-219">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="190c1-220">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-220">Access</span></span>
- <span data-ttu-id="190c1-221">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-221">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-222">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-222">Project</span></span>
- <span data-ttu-id="190c1-223">Устранена ошибка, при которой приложение Project аварийно завершало работу после перехода на панель задач</span><span class="sxs-lookup"><span data-stu-id="190c1-223">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="190c1-224">17 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-224">May 17, 2019</span></span>
<span data-ttu-id="190c1-225">Версия 1906 (сборка 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="190c1-225">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-226">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-226">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-227">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="190c1-228">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="190c1-228">User Experience Updates</span></span>

<span data-ttu-id="190c1-229">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="190c1-229">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-230">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-230">Getting Started:</span></span>

<span data-ttu-id="190c1-231">Эти изменения относятся к новому стандартному пользовательскому интерфейсу; он был доступен с помощью переключателя "Ожидается в ближайшее время" с середины декабря для 100 % рабочих сред</span><span class="sxs-lookup"><span data-stu-id="190c1-231">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="190c1-232">Настраиваемая упрощенная лента</span><span class="sxs-lookup"><span data-stu-id="190c1-232">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="190c1-233">Возможность простой настройки для переключения между классическим и упрощенным представлением, а также для закрепления и открепления команд.</span><span class="sxs-lookup"><span data-stu-id="190c1-233">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-234">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-234">Getting Started:</span></span>

<span data-ttu-id="190c1-235">Пользователи могут перейти к упрощенной ленте, включив переключатель "Ожидается в ближайшее время" (изначально) и щелкнув шеврон на ленте, чтобы переключаться между классической многострочной и новой упрощенной однострочной лентой.</span><span class="sxs-lookup"><span data-stu-id="190c1-235">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-236">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-236">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-237">Переключение с классической на упрощенную ленту</span><span class="sxs-lookup"><span data-stu-id="190c1-237">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="190c1-238">Выбор избранного действия</span><span class="sxs-lookup"><span data-stu-id="190c1-238">Pick your favorite action</span></span>

<span data-ttu-id="190c1-239">Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="190c1-239">Don't use Flag and Delete?</span></span> <span data-ttu-id="190c1-240">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="190c1-240">How about Archive or Mark as Read?</span></span> <span data-ttu-id="190c1-241">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="190c1-241">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-242">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-242">Getting Started:</span></span>

<span data-ttu-id="190c1-243">Чтобы выбрать быстрые действия, щелкните правой кнопкой мыши сообщение в списке для отображения контекстного меню.</span><span class="sxs-lookup"><span data-stu-id="190c1-243">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="190c1-244">Затем выберите пункт "Задать быстрые действия"</span><span class="sxs-lookup"><span data-stu-id="190c1-244">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-245">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-245">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-246">Изменение используемых по умолчанию действий "Пометить" и "Удалить" на "Архивировать", "Переместить", "Пометить как прочитанные" или "Отсутствует" для уменьшения элементов в списке сообщений</span><span class="sxs-lookup"><span data-stu-id="190c1-246">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="190c1-247">Самостоятельно</span><span class="sxs-lookup"><span data-stu-id="190c1-247">Relaxed or tighter layout?</span></span> <span data-ttu-id="190c1-248">выбирайте свободный или компактный макет</span><span class="sxs-lookup"><span data-stu-id="190c1-248">You choose</span></span>

<span data-ttu-id="190c1-249">С помощью компактных интервалов можно выбрать дополнительное пространство между элементами или более сжатый макет, чтобы увидеть больше элементов.</span><span class="sxs-lookup"><span data-stu-id="190c1-249">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-250">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-250">Getting Started:</span></span>

<span data-ttu-id="190c1-251">Вкладка "Вид", флажок "Уменьшить интервал" в группе "Сообщения" для классической ленты и параметры текущего представления для упрощенной ленты</span><span class="sxs-lookup"><span data-stu-id="190c1-251">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-252">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-252">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-253">Использование Outlook для просмотра и создания сообщений с включенным и отключенным параметром.</span><span class="sxs-lookup"><span data-stu-id="190c1-253">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="190c1-254">При включенном параметре "Уменьшить интервал" на странице располагается больше сообщений, а элементы управления в формах создания упрощаются.</span><span class="sxs-lookup"><span data-stu-id="190c1-254">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="190c1-255">Дедупликация недавно использовавшихся записей при применении клиента синхронизации OneDrive</span><span class="sxs-lookup"><span data-stu-id="190c1-255">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="190c1-256">Улучшите интеграцию с клиентом синхронизации OneDrive с помощью облачных вложений, выполнив дедупликацмию недавно использовавшихся записей, обеспечивающую ускорение вложения в виде копии для синхронизированных данных</span><span class="sxs-lookup"><span data-stu-id="190c1-256">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-257">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-257">Getting Started:</span></span>

<span data-ttu-id="190c1-258">При использовании клиента синхронизации OneDrive дубликаты больше не отображаются в меню последних выбиравшихся для вложений файлов.</span><span class="sxs-lookup"><span data-stu-id="190c1-258">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-259">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-259">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-260">Включение клиента синхронизации OneDrive и использование меню "Вложить файл" в классической версии Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-260">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="190c1-261">Улучшенная синхронизация общих папок для почтовых ящиков с большим числом папок</span><span class="sxs-lookup"><span data-stu-id="190c1-261">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="190c1-262">В течение нескольких лет при синхронизации общих почтовых ящиков в приложении Outlook существовало ограничение не более 500 папок.</span><span class="sxs-lookup"><span data-stu-id="190c1-262">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="190c1-263">В результате этого изменения при синхронизации в Outlook больше не будет применяться это ограничение в 500 папок.</span><span class="sxs-lookup"><span data-stu-id="190c1-263">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-264">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-264">Getting Started:</span></span>

<span data-ttu-id="190c1-265">Создайте в почтовом ящике 1000 папок, предоставьте другому пользователю доступ к почтовому ящику, создайте профиль Outlook для "другого пользователя" и убедитесь в выполнении синхронизации.</span><span class="sxs-lookup"><span data-stu-id="190c1-265">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="190c1-266">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-266">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="190c1-267">Стереть лишь небольшую часть</span><span class="sxs-lookup"><span data-stu-id="190c1-267">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-268">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-268">Getting Started:</span></span>

<span data-ttu-id="190c1-269">Откройте вкладку "Рисование". Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="190c1-269">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="190c1-270">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="190c1-270">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-271">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-271">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-272">Откройте вкладку "Рисование". Выберите перо.</span><span class="sxs-lookup"><span data-stu-id="190c1-272">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="190c1-273">Нанесите росчерк пером.</span><span class="sxs-lookup"><span data-stu-id="190c1-273">Draw an ink stroke.</span></span> <span data-ttu-id="190c1-274">Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="190c1-274">Select the Eraser dropdown.</span></span> <span data-ttu-id="190c1-275">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="190c1-275">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="190c1-276">Сотрите лишь небольшую часть росчерка пера.</span><span class="sxs-lookup"><span data-stu-id="190c1-276">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-277">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-277">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="190c1-278">Все</span><span class="sxs-lookup"><span data-stu-id="190c1-278">All</span></span> 
- <span data-ttu-id="190c1-279">Исправлена проблема, из-за которой некоторым пользователям могло не удаваться сохранять файлы в формате PDF</span><span class="sxs-lookup"><span data-stu-id="190c1-279">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="190c1-280">Исправлена проблема, которая могла влиять на сохранение пользователями больших файлов в 32-разрядной системе</span><span class="sxs-lookup"><span data-stu-id="190c1-280">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="190c1-281">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-281">Word</span></span> 
- <span data-ttu-id="190c1-282">Значительно повышена скорость реагирования функции диктовки</span><span class="sxs-lookup"><span data-stu-id="190c1-282">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-283">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-283">Excel</span></span>
- <span data-ttu-id="190c1-284">Исправлена проблема, из-за которой события двойного щелчка могли не срабатывать на устройствах с сенсорным экраном</span><span class="sxs-lookup"><span data-stu-id="190c1-284">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="190c1-285">Исправлена проблема, которая могла блокировать для некоторых пользователей редактирование макросов VBA</span><span class="sxs-lookup"><span data-stu-id="190c1-285">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="190c1-286">Исправлена проблема, которая могла влиять на производительность при использовании срезов</span><span class="sxs-lookup"><span data-stu-id="190c1-286">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-287">PowerPoint</span></span>
- <span data-ttu-id="190c1-288">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-288">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-289">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-289">Outlook</span></span>
- <span data-ttu-id="190c1-290">Исправлена проблема, из-за которой неверный шаблон мог отображаться среди выбранных</span><span class="sxs-lookup"><span data-stu-id="190c1-290">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="190c1-291">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-291">Access</span></span>
- <span data-ttu-id="190c1-292">Исправлена проблема, из-за которой могло быть затруднено чтение текста при использовании построителя масштаба для отображения длинного форматированного текста</span><span class="sxs-lookup"><span data-stu-id="190c1-292">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="190c1-293">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-293">Project</span></span>
- <span data-ttu-id="190c1-294">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-294">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="190c1-295">10 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-295">May 10, 2019</span></span>
<span data-ttu-id="190c1-296">Версия 1906 (сборка 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="190c1-296">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-297">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-297">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="190c1-298">Все</span><span class="sxs-lookup"><span data-stu-id="190c1-298">All</span></span>
- <span data-ttu-id="190c1-299">Исправлена проблема, из-за которой диалоговое окно "Сохранить как" могло отображать неправильный путь</span><span class="sxs-lookup"><span data-stu-id="190c1-299">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="190c1-300">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-300">Word</span></span> 
- <span data-ttu-id="190c1-301">Исправлена проблема, из-за которой не вставлялись некоторые выбранные элементы из области "Что вы хотите сделать?"</span><span class="sxs-lookup"><span data-stu-id="190c1-301">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-302">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-302">Excel</span></span>
- <span data-ttu-id="190c1-303">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-303">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-304">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-304">PowerPoint</span></span>
- <span data-ttu-id="190c1-305">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-305">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-306">Outlook</span></span>
- <span data-ttu-id="190c1-307">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-307">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="190c1-308">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-308">Access</span></span>
- <span data-ttu-id="190c1-309">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-309">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-310">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-310">Project</span></span>
- <span data-ttu-id="190c1-311">Исправлена проблема, из-за которой могло требоваться выделение для просмотра идентификатора задачи</span><span class="sxs-lookup"><span data-stu-id="190c1-311">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="190c1-312">3 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-312">May 3, 2019</span></span>
<span data-ttu-id="190c1-313">Версия 1906 (сборка 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="190c1-313">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-314">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-314">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="190c1-315">Все</span><span class="sxs-lookup"><span data-stu-id="190c1-315">All</span></span>
- <span data-ttu-id="190c1-316">Исправлена ошибка, из-за которой у некоторых пользователей возникали проблемы с синхронизацией OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="190c1-316">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="190c1-317">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-317">Word</span></span> 
- <span data-ttu-id="190c1-318">Исправлена ошибка, из-за которой в некоторых случаях запуск Word занимал много времени</span><span class="sxs-lookup"><span data-stu-id="190c1-318">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-319">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-319">Excel</span></span>
- <span data-ttu-id="190c1-320">Исправлена проблема, из-за которой внешние ссылки иногда удалялись из книг после обновления до более новой версии Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-320">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="190c1-321">Исправлена проблема, из-за которой у некоторых пользователей могли возникать сложности с выделением ячеек в новой книге</span><span class="sxs-lookup"><span data-stu-id="190c1-321">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-322">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-322">PowerPoint</span></span>
- <span data-ttu-id="190c1-323">Исправлена проблема, из-за которой при преобразовании рисунков в текст неправильно согласовывались размеры шрифтов</span><span class="sxs-lookup"><span data-stu-id="190c1-323">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-324">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-324">Outlook</span></span>
- <span data-ttu-id="190c1-325">Исправлена проблема, из-за которой сохранение контакта из VCF-файла могло привести к получению пустых полей</span><span class="sxs-lookup"><span data-stu-id="190c1-325">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="190c1-326">Исправлена проблема, из-за которой сообщение могло оставаться в папке "Исходящие", хотя оно было отправлено</span><span class="sxs-lookup"><span data-stu-id="190c1-326">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="190c1-327">Исправлена проблема с аварийным завершением работы Outlook при просмотре сообщения DRM</span><span class="sxs-lookup"><span data-stu-id="190c1-327">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="190c1-328">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-328">Access</span></span>
- <span data-ttu-id="190c1-329">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-329">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-330">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-330">Project</span></span>
- <span data-ttu-id="190c1-331">Устранена ошибка, при которой редактор менялся с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="190c1-331">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="190c1-332">Устранена проблема, из-за которой неопубликованные задачи могли отображаться в опубликованной копии главного проекта</span><span class="sxs-lookup"><span data-stu-id="190c1-332">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="190c1-333">26 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-333">April 26, 2019</span></span>
<span data-ttu-id="190c1-334">Версия 1905 (сборка 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="190c1-334">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-335">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-335">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-336">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-336">Word</span></span> 
- <span data-ttu-id="190c1-337">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-337">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-338">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-338">Excel</span></span>
- <span data-ttu-id="190c1-339">Устранена проблема, которая приводила к невозможности запуска макросов надстройки "Поиск решения"</span><span class="sxs-lookup"><span data-stu-id="190c1-339">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="190c1-340">Устранена проблема, которая могла препятствовать импорту файлов Excel в SharePoint</span><span class="sxs-lookup"><span data-stu-id="190c1-340">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-341">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-341">PowerPoint</span></span>
- <span data-ttu-id="190c1-342">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-342">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-343">Outlook</span></span>
- <span data-ttu-id="190c1-344">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-344">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="190c1-345">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-345">Access</span></span>
- <span data-ttu-id="190c1-346">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-346">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-347">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-347">Project</span></span>
- <span data-ttu-id="190c1-348">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-348">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="190c1-349">19 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-349">April 19, 2019</span></span>
<span data-ttu-id="190c1-350">Версия 1905 (сборка 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="190c1-350">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-351">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-351">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-352">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-352">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="190c1-353">Улучшенный интерфейс картограмм с использованием типов данных</span><span class="sxs-lookup"><span data-stu-id="190c1-353">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="190c1-354">Эта возможность является улучшением для пользователей, создающих картограммы с использованием географических типов данных Excel.</span><span class="sxs-lookup"><span data-stu-id="190c1-354">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="190c1-355">Преимущество для пользователей заключается в более глубокой интеграции функций и повышенной точности в области, которую пользователь хочет отобразить на карте.</span><span class="sxs-lookup"><span data-stu-id="190c1-355">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="190c1-356">Дополнительные преимущества включают возможность нанесения на карту многоугольников городов.</span><span class="sxs-lookup"><span data-stu-id="190c1-356">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="190c1-357">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-357">Getting Started:</span></span>

- <span data-ttu-id="190c1-358">Эта возможность является улучшением существующих функций в Excel.</span><span class="sxs-lookup"><span data-stu-id="190c1-358">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="190c1-359">Чтобы использовать улучшение, преобразуйте расположения в объекты Rich и выполните построение с помощью картограмм.</span><span class="sxs-lookup"><span data-stu-id="190c1-359">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-360">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-360">Scenarios to Try:</span></span>

- <span data-ttu-id="190c1-361">Пользователи могут попробовать указать на картах города, регионы, районы, страны и почтовые индексы.</span><span class="sxs-lookup"><span data-stu-id="190c1-361">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="190c1-362">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-362">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="190c1-363">Все приложения</span><span class="sxs-lookup"><span data-stu-id="190c1-363">All Applications</span></span>
- <span data-ttu-id="190c1-364">Исправлена ошибка, из-за которой диалоговое окно первого запуска отображалось при каждом запуске приложения</span><span class="sxs-lookup"><span data-stu-id="190c1-364">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="190c1-365">Исправлена ошибка с возможным отсутствием ссылки SharePoint в диалоговом окне "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="190c1-365">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="190c1-366">Исправлена ошибка, из-за которой для пользователей неправильно отображалось диалоговое окно "Восстановить"</span><span class="sxs-lookup"><span data-stu-id="190c1-366">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="190c1-367">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-367">Word</span></span> 
- <span data-ttu-id="190c1-368">Исправлена ошибка, из-за которой у некоторых пользователей могла возникать ошибка с сообщением о недостатке памяти или места на диске при запросе шрифта</span><span class="sxs-lookup"><span data-stu-id="190c1-368">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="190c1-369">Исправлена ошибка, из-за которой мог теряться фокус окна при переходе из области примечаний</span><span class="sxs-lookup"><span data-stu-id="190c1-369">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-370">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-370">Excel</span></span>
- <span data-ttu-id="190c1-371">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-371">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-372">PowerPoint</span></span>
- <span data-ttu-id="190c1-373">Исправлена ошибка, не позволявшая изменять размер фигур с фирменной символикой</span><span class="sxs-lookup"><span data-stu-id="190c1-373">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="190c1-374">Исправлена ошибка, из-за которой приложение PowerPoint могло аварийно завершать работу при открытии файла в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="190c1-374">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-375">Outlook</span></span>
- <span data-ttu-id="190c1-376">Исправлена ошибка, не позволявшая некоторым пользователям выделять китайские слова</span><span class="sxs-lookup"><span data-stu-id="190c1-376">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="190c1-377">Исправлена ошибка с неправильным вычислением сроков действия</span><span class="sxs-lookup"><span data-stu-id="190c1-377">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="190c1-378">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-378">Access</span></span>
- <span data-ttu-id="190c1-379">Исправлена ошибка, не позволявшая некоторым пользователям применять построитель макросов</span><span class="sxs-lookup"><span data-stu-id="190c1-379">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="190c1-380">Исправлена ошибка, из-за которой при печати отчета печаталась только первая страница</span><span class="sxs-lookup"><span data-stu-id="190c1-380">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="190c1-381">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при наведении указателя на гиперссылку</span><span class="sxs-lookup"><span data-stu-id="190c1-381">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="190c1-382">Исправлена проблема, приводившая к отображению некоторых элементов вне экрана при использовании представления "Схема данных"</span><span class="sxs-lookup"><span data-stu-id="190c1-382">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="190c1-383">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-383">Project</span></span>
- <span data-ttu-id="190c1-384">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-384">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="190c1-385">12 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-385">April 12, 2019</span></span>
<span data-ttu-id="190c1-386">Версия 1905 (сборка 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="190c1-386">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-387">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-387">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="190c1-388">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-388">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="190c1-389">Новая возможность в Access: соединитель данных с Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="190c1-389">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="190c1-390">Связывайтесь со службами Microsoft Graph или импортируйте из них данные, чтобы создавать приложения, использующие интеллектуальные контекстные данные, хранящиеся в Graph</span><span class="sxs-lookup"><span data-stu-id="190c1-390">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-391">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-391">Getting Started:</span></span>

<span data-ttu-id="190c1-392">На вкладке ленты "Внешние данные" нажмите кнопку "Создать источник данных" и найдите новый соединитель Graph в меню "Из Online Services".</span><span class="sxs-lookup"><span data-stu-id="190c1-392">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-393">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-393">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-394">Импорт из различных служб Graph или связывание с ними, включая службы "Люди", "Группы" и "Элементы OneDrive".</span><span class="sxs-lookup"><span data-stu-id="190c1-394">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-395">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-395">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="190c1-396">Все приложения</span><span class="sxs-lookup"><span data-stu-id="190c1-396">All Applications</span></span>
 - <span data-ttu-id="190c1-397">Исправлена ошибка, не позволявшая некоторым пользователям сохранять файлы в облачных расположениях</span><span class="sxs-lookup"><span data-stu-id="190c1-397">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="190c1-398">Исправлена ошибка, из-за которой могла открываться неправильная область из ленты</span><span class="sxs-lookup"><span data-stu-id="190c1-398">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="190c1-399">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-399">Word</span></span> 
- <span data-ttu-id="190c1-400">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-400">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-401">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-401">Excel</span></span>
- <span data-ttu-id="190c1-402">Исправлена ошибка, из-за которой для пользователей отображалось сообщение об ошибке, относящееся к связанным типам данных, если книга не содержала связанные типы данных</span><span class="sxs-lookup"><span data-stu-id="190c1-402">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="190c1-403">Исправлена ошибка, из-за которой URL-ссылки в документе Word могли изменяться в зависимости от способа просмотра (локально или в Интернете)</span><span class="sxs-lookup"><span data-stu-id="190c1-403">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-404">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-404">PowerPoint</span></span>
- <span data-ttu-id="190c1-405">Исправлена ошибка, из-за которой мог происходить сбой приложения после отмены всех изменений на вкладке "Анимация"</span><span class="sxs-lookup"><span data-stu-id="190c1-405">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-406">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-406">Outlook</span></span>
- <span data-ttu-id="190c1-407">Исправлена ошибка, не позволявшая некоторым пользователям изменять поле "Заметки" для контактов в общедоступной папке</span><span class="sxs-lookup"><span data-stu-id="190c1-407">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="190c1-408">Исправлена ошибка, из-за которой мог возникать конфликт между датами окончания срока действия и датами удаления</span><span class="sxs-lookup"><span data-stu-id="190c1-408">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="190c1-409">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-409">Access</span></span>
- <span data-ttu-id="190c1-410">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-410">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-411">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-411">Project</span></span>
- <span data-ttu-id="190c1-412">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-412">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="190c1-413">5 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-413">April 5, 2019</span></span>
<span data-ttu-id="190c1-414">Версия 1904 (сборка 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="190c1-414">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-415">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-415">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-416">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-416">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="190c1-417">Outlook для Windows: настройка параметров сортировки почты и предоставление к ним общего доступа</span><span class="sxs-lookup"><span data-stu-id="190c1-417">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="190c1-418">Ваши параметры сортировки почты хранятся в облаке, поэтому можно наслаждаться единообразным интерфейсом при использовании Outlook для Windows и Outlook в Интернете с любого устройства.</span><span class="sxs-lookup"><span data-stu-id="190c1-418">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-419">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-419">Getting Started:</span></span>

<span data-ttu-id="190c1-420">На вкладке "Общие" в разделе "Файл" > "Параметры" есть новый параметр "Хранить мои параметры Outlook в облаке".</span><span class="sxs-lookup"><span data-stu-id="190c1-420">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="190c1-421">Пользователям нужно установить флажок, чтобы разрешить перенос параметра сортировки почты в другие экземпляры классической версии Outlook и Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="190c1-421">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-422">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-422">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-423">Измените сортировку почты на компьютере с включенными облачными параметрами.</span><span class="sxs-lookup"><span data-stu-id="190c1-423">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="190c1-424">Перейдите в Outlook Web App и убедитесь, что этот параметр также применен.</span><span class="sxs-lookup"><span data-stu-id="190c1-424">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="190c1-425">Измените настройки сортировки почты в Outlook Web App и запустите классическую версию Outlook, чтобы увидеть применение этих настроек.</span><span class="sxs-lookup"><span data-stu-id="190c1-425">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="190c1-426">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-426">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="190c1-427">В режиме "Средства обучения" реализована поддержка дополнительных цветов страниц</span><span class="sxs-lookup"><span data-stu-id="190c1-427">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="190c1-428">Средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="190c1-428">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="190c1-429">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="190c1-429">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-430">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-430">Getting Started:</span></span>

<span data-ttu-id="190c1-431">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="190c1-431">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-432">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-432">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-433">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="190c1-433">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-434">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-434">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="190c1-435">Расширение возможностей для творчества с помощью анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="190c1-435">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="190c1-436">Теперь Office поддерживает анимированные модели, воспроизводимые в редакторе, чтобы вы могли оживить свои листы!</span><span class="sxs-lookup"><span data-stu-id="190c1-436">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-437">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-437">Getting Started:</span></span>

1. <span data-ttu-id="190c1-438">Откройте Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-438">Open Excel.</span></span>
2. <span data-ttu-id="190c1-439">Вставьте анимированную трехмерную модель (вскоре будут доступны в сообществе Remix, а пока их можно найти здесь: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="190c1-439">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="190c1-440">Анимированная модель будет воспроизводиться в редакторе!</span><span class="sxs-lookup"><span data-stu-id="190c1-440">The animated model will play in the editor!</span></span> <span data-ttu-id="190c1-441">Проверьте режим слайд-шоу, она будет воспроизводиться и там!</span><span class="sxs-lookup"><span data-stu-id="190c1-441">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="190c1-442">На ленте форматирования трехмерных моделей можно ознакомиться с дополнительными анимационными сценами в модели</span><span class="sxs-lookup"><span data-stu-id="190c1-442">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-443">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-443">Scenarios to Try:</span></span>

1. <span data-ttu-id="190c1-444">Вставьте анимированную модель и посмотрите, как она будет воспроизводиться в редакторе</span><span class="sxs-lookup"><span data-stu-id="190c1-444">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="190c1-445">Узнайте, какие анимационные сцены доступны для анимированной модели в коллекции "Сцены" на ленте форматирования трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="190c1-445">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="190c1-446">Можно воспроизводить или приостанавливать анимацию с помощью ленты, мини-панели или клавиши ПРОБЕЛ.</span><span class="sxs-lookup"><span data-stu-id="190c1-446">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-447">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-447">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="190c1-448">Все приложения</span><span class="sxs-lookup"><span data-stu-id="190c1-448">All Applications</span></span>
- <span data-ttu-id="190c1-449">Мы исправили ошибку, когда значок приложения для Excel может отображаться неправильно в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="190c1-449">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="190c1-450">Мы исправили ошибку, когда после установки обновления может исчезать кнопка меню "Файл".</span><span class="sxs-lookup"><span data-stu-id="190c1-450">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="190c1-451">Исправлена проблема, в результате которой может измениться пользовательская лицензия.</span><span class="sxs-lookup"><span data-stu-id="190c1-451">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="190c1-452">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-452">Word</span></span> 
- <span data-ttu-id="190c1-453">Исправлена проблема с неправильным отображением текста при определенных уровнях масштабирования.</span><span class="sxs-lookup"><span data-stu-id="190c1-453">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-454">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-454">Excel</span></span>
- <span data-ttu-id="190c1-455">Мы исправили ошибку, в результате которой пользователи могли не видеть запрос на сохранение книги после внесения изменений.</span><span class="sxs-lookup"><span data-stu-id="190c1-455">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="190c1-456">Мы исправили ошибку, когда событие BeforeSave не запускалось, если пользователь предоставил общий доступ к книге.</span><span class="sxs-lookup"><span data-stu-id="190c1-456">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="190c1-457">Исправлена проблема, когда изменение размера столбца на менее чем 6 пикселей вызывает появление сообщения об ошибке.</span><span class="sxs-lookup"><span data-stu-id="190c1-457">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="190c1-458">Исправлена ошибка, когда Excel игнорирует метку Application.Visible.</span><span class="sxs-lookup"><span data-stu-id="190c1-458">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="190c1-459">Исправлена ошибка, когда стрелки трассировки остаются на неактивных закрепленных областях.</span><span class="sxs-lookup"><span data-stu-id="190c1-459">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="190c1-460">Исправлена ошибка, когда форматирование ячеек дат и валют может изменяться при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="190c1-460">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="190c1-461">Мы исправили ошибку, когда подсказки могли неожиданно перемещаться</span><span class="sxs-lookup"><span data-stu-id="190c1-461">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="190c1-462">Мы исправили ошибки локализации редактора Power Query</span><span class="sxs-lookup"><span data-stu-id="190c1-462">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="190c1-463">Мы устранили проблему, когда рабочая книга могла удаляться из вложений при отправке по электронной почте.</span><span class="sxs-lookup"><span data-stu-id="190c1-463">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-464">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-464">PowerPoint</span></span>
- <span data-ttu-id="190c1-465">Мы устранили проблему с длительным временем, которое может требоваться на копирование форм.</span><span class="sxs-lookup"><span data-stu-id="190c1-465">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-466">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-466">Outlook</span></span>
- <span data-ttu-id="190c1-467">Мы устранили проблему с аварийным завершением работы Outlook при использовании инструмента рисования</span><span class="sxs-lookup"><span data-stu-id="190c1-467">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="190c1-468">Устранена проблема локализации при составлении HTML-сообщений электронной почты</span><span class="sxs-lookup"><span data-stu-id="190c1-468">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="190c1-469">Мы устранили проблему, когда пользователи сталкивались с трудностями при выборе нижней панели</span><span class="sxs-lookup"><span data-stu-id="190c1-469">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="190c1-470">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-470">Access</span></span>
- <span data-ttu-id="190c1-471">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-471">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-472">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-472">Project</span></span>
- <span data-ttu-id="190c1-473">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-473">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="190c1-474">22 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-474">March 22, 2019</span></span>
<span data-ttu-id="190c1-475">Версия 1904 (сборка 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="190c1-475">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-476">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-476">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-477">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-477">Word</span></span> 
- <span data-ttu-id="190c1-478">Устранена ошибка, при которой в интерфейсе пользователя постоянно отображается "Проверка изменений".</span><span class="sxs-lookup"><span data-stu-id="190c1-478">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-479">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-479">Excel</span></span>
- <span data-ttu-id="190c1-480">Устранена ошибка, при которой приложение аварийно завершало работу после перемещения листа</span><span class="sxs-lookup"><span data-stu-id="190c1-480">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="190c1-481">Устранена ошибка, при которой приложение аварийно завершало работу после сохранения в формате PDF</span><span class="sxs-lookup"><span data-stu-id="190c1-481">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="190c1-482">Устранена ошибка, при которой диалоговое окно сохранения не воспринимало некоторые корейские символы</span><span class="sxs-lookup"><span data-stu-id="190c1-482">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-483">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-483">PowerPoint</span></span>
- <span data-ttu-id="190c1-484">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-484">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-485">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-485">Outlook</span></span>
- <span data-ttu-id="190c1-486">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-486">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="190c1-487">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-487">Access</span></span>
- <span data-ttu-id="190c1-488">Исправлено сообщение об ошибке в Access, при которой создавался дополнительный ярлык для Access</span><span class="sxs-lookup"><span data-stu-id="190c1-488">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="190c1-489">Устранена ошибка, при которой данные со связанного сайта SharePoint отображались неправильно</span><span class="sxs-lookup"><span data-stu-id="190c1-489">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="190c1-490">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-490">Project</span></span>
- <span data-ttu-id="190c1-491">Устранена ошибка, при которой языковые параметры менялись с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="190c1-491">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="190c1-492">Устранена ошибка, при которой приложение аварийно завершало работу при синхронизации с SharePoint</span><span class="sxs-lookup"><span data-stu-id="190c1-492">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="190c1-493">15 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-493">March 15, 2019</span></span>
<span data-ttu-id="190c1-494">Версия 1904 (сборка 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="190c1-494">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-495">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-495">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-496">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-496">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="190c1-497">Режим фокусировки</span><span class="sxs-lookup"><span data-stu-id="190c1-497">Focus mode</span></span>

<span data-ttu-id="190c1-498">Хотите, чтобы вас ничего не отвлекало от работы? Переключитесь в режим фокусировки в меню "Вид".</span><span class="sxs-lookup"><span data-stu-id="190c1-498">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="190c1-499">Только для обладателей подписки на Office 365.</span><span class="sxs-lookup"><span data-stu-id="190c1-499">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-500">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-500">Getting Started:</span></span>

<span data-ttu-id="190c1-501">Кнопка "Фокус" вкладки "Вид" в строке состояния ленты с кнопкой "Фокус"</span><span class="sxs-lookup"><span data-stu-id="190c1-501">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-502">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-502">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-503">Переход в режим фокусировки и работа в интерфейсе фокусировки</span><span class="sxs-lookup"><span data-stu-id="190c1-503">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-504">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-505">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-505">Word</span></span> 
- <span data-ttu-id="190c1-506">Исправлена проблема, из-за которой изображения в документе, сохраненном в формате PDF, имели неправильное значение точек на дюйм</span><span class="sxs-lookup"><span data-stu-id="190c1-506">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-507">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-507">Excel</span></span>
- <span data-ttu-id="190c1-508">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-508">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-509">PowerPoint</span></span>
- <span data-ttu-id="190c1-510">Исправлена проблема, из-за которой область примечаний открывалась и закрывалась неправильно</span><span class="sxs-lookup"><span data-stu-id="190c1-510">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="190c1-511">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при удалении видео</span><span class="sxs-lookup"><span data-stu-id="190c1-511">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="190c1-512">Исправлена проблема, когда некоторые экземпляры приложения не запускались.</span><span class="sxs-lookup"><span data-stu-id="190c1-512">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-513">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-513">Outlook</span></span>
- <span data-ttu-id="190c1-514">Исправлена проблема с неправильными уведомлениями о прочтении при просмотре на японском языке.</span><span class="sxs-lookup"><span data-stu-id="190c1-514">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="190c1-515">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-515">Access</span></span>
- <span data-ttu-id="190c1-516">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-516">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-517">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-517">Project</span></span>
- <span data-ttu-id="190c1-518">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-518">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="190c1-519">8 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-519">March 8, 2019</span></span> 
<span data-ttu-id="190c1-520">Версия 1903 (сборка 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="190c1-520">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-521">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-521">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-522">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-522">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="190c1-523">Находите нужные элементы с помощью Поиска (Майкрософт)</span><span class="sxs-lookup"><span data-stu-id="190c1-523">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="190c1-524">С помощью поиска Майкрософт можно найти все файлы, команды и пользователей, которые необходимы для выполнения работы.</span><span class="sxs-lookup"><span data-stu-id="190c1-524">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-525">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-525">Getting Started:</span></span>

- <span data-ttu-id="190c1-526">Эта функция выделяется вверху пользовательского интерфейса в заголовке.</span><span class="sxs-lookup"><span data-stu-id="190c1-526">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-527">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-527">Scenarios to Try:</span></span>

- <span data-ttu-id="190c1-528">Поиск учебного заведения, недавнего документа или часто используемых команд ленты</span><span class="sxs-lookup"><span data-stu-id="190c1-528">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="190c1-529">Поиск статьи или темы и получение дополнительных сведений о ней</span><span class="sxs-lookup"><span data-stu-id="190c1-529">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="190c1-530">Совместное редактирование</span><span class="sxs-lookup"><span data-stu-id="190c1-530">CoAuthoring</span></span>

<span data-ttu-id="190c1-531">Вам надоело получать блокировку на документы с макросами?</span><span class="sxs-lookup"><span data-stu-id="190c1-531">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="190c1-532">Теперь DOCM-файлы в OneDrive для бизнеса поддерживают одновременное редактирование несколькими авторами.</span><span class="sxs-lookup"><span data-stu-id="190c1-532">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-533">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-533">Getting Started:</span></span>

<span data-ttu-id="190c1-534">Пользователю не нужно нажимать какие-либо кнопки в пользовательском интерфейсе, чтобы применить эту возможность.</span><span class="sxs-lookup"><span data-stu-id="190c1-534">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="190c1-535">Она включена по умолчанию для DOCM-файлов в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="190c1-535">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="190c1-536">Чтобы применить ее, пользователю нужно сохранить DOCM-файл в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="190c1-536">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-537">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-537">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-538">Создайте DOCM-файл в OneDrive для бизнеса, поделитесь им с коллегами и работайте совместно!</span><span class="sxs-lookup"><span data-stu-id="190c1-538">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-539">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-539">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-540">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-540">Word</span></span> 
- <span data-ttu-id="190c1-541">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="190c1-541">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="190c1-542">Решена проблема со сбоем, происходившим при ответе на примечания</span><span class="sxs-lookup"><span data-stu-id="190c1-542">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="190c1-543">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="190c1-543">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-544">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-544">Excel</span></span>
- <span data-ttu-id="190c1-545">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="190c1-545">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-546">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-546">PowerPoint</span></span>
- <span data-ttu-id="190c1-547">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-547">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-548">Outlook</span></span>
- <span data-ttu-id="190c1-549">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="190c1-549">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="190c1-550">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="190c1-550">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="190c1-551">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="190c1-551">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="190c1-552">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-552">Access</span></span>
- <span data-ttu-id="190c1-553">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="190c1-553">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="190c1-554">Исправлена проблема, из-за которой пользователи не могли присвоить свойству DisplayControl для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="190c1-554">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="190c1-555">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-555">Project</span></span>
- <span data-ttu-id="190c1-556">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-556">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="190c1-557">1 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-557">March 1, 2019</span></span> 
<span data-ttu-id="190c1-558">Версия 1903 (сборка 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="190c1-558">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-559">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="190c1-559">What's New</span></span>

### <a name="word"></a><span data-ttu-id="190c1-560">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-560">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="190c1-561">Синхронизированные цвета для отслеживания изменений, примечаний и совместной работы в режиме реального времени</span><span class="sxs-lookup"><span data-stu-id="190c1-561">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="190c1-562">Исправления в наших продуктах теперь обеспечивают отображение одинаковым цветом примечаний, изменений и указателя мыши при совместной работе.</span><span class="sxs-lookup"><span data-stu-id="190c1-562">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-563">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-563">Getting Started:</span></span>

<span data-ttu-id="190c1-564">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="190c1-564">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="190c1-565">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="190c1-565">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-566">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-566">Scenarios to Try:</span></span>

<span data-ttu-id="190c1-567">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="190c1-567">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="190c1-568">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="190c1-568">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-569">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-569">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-570">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-570">Word</span></span> 
- <span data-ttu-id="190c1-571">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="190c1-571">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="190c1-572">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="190c1-572">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-573">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-573">Excel</span></span>
- <span data-ttu-id="190c1-574">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="190c1-574">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-575">PowerPoint</span></span>
- <span data-ttu-id="190c1-576">Исправлена проблема с размером изображения слайда при использовании @упоминаний в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-576">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-577">Outlook</span></span>
- <span data-ttu-id="190c1-578">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="190c1-578">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="190c1-579">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="190c1-579">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="190c1-580">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="190c1-580">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="190c1-581">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-581">Access</span></span>
- <span data-ttu-id="190c1-582">Обновлен текст запроса, отображаемый для подтверждения обновления связей таблицы с источником данных</span><span class="sxs-lookup"><span data-stu-id="190c1-582">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="190c1-583">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="190c1-583">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="190c1-584">Исправлена проблема, из-за которой пользователи не могли присвоить свойству "Тип элемента управления" для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="190c1-584">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="190c1-585">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-585">Project</span></span>
- <span data-ttu-id="190c1-586">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-586">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="190c1-587">15 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-587">February 15, 2019</span></span> 
<span data-ttu-id="190c1-588">Версия 1903 (сборка 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="190c1-588">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="190c1-589">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="190c1-589">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-590">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="190c1-591">Улучшения перехода "Трансформация" — трансформация по имени</span><span class="sxs-lookup"><span data-stu-id="190c1-591">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="190c1-592">Укажите фигуры, которые нужно трансформировать</span><span class="sxs-lookup"><span data-stu-id="190c1-592">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-593">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-593">Getting Started:</span></span>

- <span data-ttu-id="190c1-594">Чтобы при переходе "Трансформация" два объекта обрабатывались как одинаковые, пользователь может переименовать фигуры с помощью области выделения.</span><span class="sxs-lookup"><span data-stu-id="190c1-594">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="190c1-595">Имя должно начинаться с двух восклицательных знаков</span><span class="sxs-lookup"><span data-stu-id="190c1-595">The name must be prefaced with “!!”</span></span> <span data-ttu-id="190c1-596">("!!"), чтобы использовать его при трансформации для переопределения стандартного сопоставления, например "!!Имя".</span><span class="sxs-lookup"><span data-stu-id="190c1-596">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="190c1-597">Пользователи могут продолжать переименовывать фигуры, используя любые имена, которые не начинаются с "!!",</span><span class="sxs-lookup"><span data-stu-id="190c1-597">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="190c1-598">не беспокоясь о том, что это изменит работу перехода "Трансформация".</span><span class="sxs-lookup"><span data-stu-id="190c1-598">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-599">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-599">Scenarios to Try:</span></span>

- <span data-ttu-id="190c1-600">Вставьте фигуру на слайд, например прямоугольник</span><span class="sxs-lookup"><span data-stu-id="190c1-600">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="190c1-601">Создайте новый слайд</span><span class="sxs-lookup"><span data-stu-id="190c1-601">Create a new slide</span></span>
- <span data-ttu-id="190c1-602">Вставьте другую фигуру на втором слайде, например треугольник</span><span class="sxs-lookup"><span data-stu-id="190c1-602">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="190c1-603">Откройте область выделения и присвойте имя "!!фигура" прямоугольнику на слайде 1 и треугольнику на слайде 2.</span><span class="sxs-lookup"><span data-stu-id="190c1-603">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="190c1-604">Примените переход "Трансформация" ко второму слайду</span><span class="sxs-lookup"><span data-stu-id="190c1-604">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="190c1-605">Улучшения перехода "Трансформация" — графические элементы SmartArt</span><span class="sxs-lookup"><span data-stu-id="190c1-605">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="190c1-606">Трансформация графических элементов SmartArt с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="190c1-606">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-607">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-607">Getting Started:</span></span>

<span data-ttu-id="190c1-608">Аналогичное использование перехода "Трансформация" при применении графических элементов SmartArt</span><span class="sxs-lookup"><span data-stu-id="190c1-608">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-609">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-609">Scenarios to Try:</span></span>

- <span data-ttu-id="190c1-610">Вставьте графический элемент SmartArt на слайд</span><span class="sxs-lookup"><span data-stu-id="190c1-610">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="190c1-611">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="190c1-611">Duplicate the Slide</span></span>
- <span data-ttu-id="190c1-612">Поменяйте размер, измените или переместите графический элемент SmartArt на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="190c1-612">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="190c1-613">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="190c1-613">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="190c1-614">Улучшения перехода "Трансформация" — таблицы</span><span class="sxs-lookup"><span data-stu-id="190c1-614">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="190c1-615">Трансформация таблиц с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="190c1-615">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="190c1-616">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="190c1-616">Getting Started:</span></span>
<span data-ttu-id="190c1-617">Аналогичное использование перехода "Трансформация" при применении таблиц</span><span class="sxs-lookup"><span data-stu-id="190c1-617">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-618">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-618">Scenarios to Try:</span></span>

- <span data-ttu-id="190c1-619">Вставьте таблицу на слайд</span><span class="sxs-lookup"><span data-stu-id="190c1-619">Insert a Table in a slide</span></span>
- <span data-ttu-id="190c1-620">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="190c1-620">Duplicate the slide</span></span>
- <span data-ttu-id="190c1-621">Поменяйте размер, измените или переместите таблицу на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="190c1-621">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="190c1-622">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="190c1-622">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="190c1-623">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher и Visio</span><span class="sxs-lookup"><span data-stu-id="190c1-623">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="190c1-624">Легкое переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="190c1-624">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="190c1-625">Новый диспетчер учетных записей отображает все рабочие и личные учетные записи в одном месте и позволяет управлять переключением между ними.</span><span class="sxs-lookup"><span data-stu-id="190c1-625">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="190c1-626">Этот обновленный интерфейс уточняет способ выполненного входа и обеспечивает возможность переключения между рабочими и личными учетными записями без выхода из системы или появления сложных диалоговых окон.</span><span class="sxs-lookup"><span data-stu-id="190c1-626">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="190c1-628">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="190c1-628">Scenarios to Try:</span></span>
- <span data-ttu-id="190c1-629">Переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="190c1-629">Switch between accounts</span></span>
- <span data-ttu-id="190c1-630">Добавление новой учетной записи [Примечание. Рекомендуется сначала открыть "Файл" | "Учетная запись" | "Подключенные службы" и удалить все личные службы, подключенные к рабочей учетной записи и наоборот]</span><span class="sxs-lookup"><span data-stu-id="190c1-630">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="190c1-631">Выход из учетной записи</span><span class="sxs-lookup"><span data-stu-id="190c1-631">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="190c1-632">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-632">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-633">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-633">Word</span></span> 
- <span data-ttu-id="190c1-634">Исправлена проблема с предварительным просмотром контекста для таблиц и изображений</span><span class="sxs-lookup"><span data-stu-id="190c1-634">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-635">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-635">Excel</span></span>
- <span data-ttu-id="190c1-636">Исправлена ошибка, из-за которой при использовании темы "Черная" текст в поле поиска автофильтра был белого цвета</span><span class="sxs-lookup"><span data-stu-id="190c1-636">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="190c1-637">Исправлена проблема с согласованным пользовательским интерфейсом для новой надстройки Office</span><span class="sxs-lookup"><span data-stu-id="190c1-637">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-638">PowerPoint</span></span>
- <span data-ttu-id="190c1-639">Исправлена проблема с автоматическим расширением области отображения во время презентации на ноутбуках и планшетах.</span><span class="sxs-lookup"><span data-stu-id="190c1-639">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-640">Outlook</span></span>
- <span data-ttu-id="190c1-641">Исправлена проблема с отображением кнопки "Отправить в OneNote"</span><span class="sxs-lookup"><span data-stu-id="190c1-641">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="190c1-642">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-642">Access</span></span>
- <span data-ttu-id="190c1-643">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-643">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-644">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-644">Project</span></span>
- <span data-ttu-id="190c1-645">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-645">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="190c1-646">11 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-646">February 11, 2019</span></span>
<span data-ttu-id="190c1-647">Версия 1903 (сборка 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="190c1-647">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="190c1-648">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-648">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="190c1-649">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-649">Word</span></span> 
- <span data-ttu-id="190c1-650">Исправлена ошибка, из-за которой некоторые настроенные стили нельзя было применить в Word Online</span><span class="sxs-lookup"><span data-stu-id="190c1-650">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="190c1-651">Исправлены проблемы предварительного просмотра контекста, связанные с форматированными объектами в Word</span><span class="sxs-lookup"><span data-stu-id="190c1-651">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="190c1-652">Исправлена ошибка, из-за которой при вставке списков происходил сбой Word.</span><span class="sxs-lookup"><span data-stu-id="190c1-652">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-653">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-653">Excel</span></span>
- <span data-ttu-id="190c1-654">Исправлена ошибка, из-за которой добавляемые пробелы после числовых форматов не отображались при отсутствии обозначения денежной единицы</span><span class="sxs-lookup"><span data-stu-id="190c1-654">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="190c1-655">Исправлена проблема с автоматическим определением акций</span><span class="sxs-lookup"><span data-stu-id="190c1-655">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-656">PowerPoint</span></span>
- <span data-ttu-id="190c1-657">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-657">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-658">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-658">Outlook</span></span>
- <span data-ttu-id="190c1-659">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-659">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="190c1-660">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-660">Access</span></span>
- <span data-ttu-id="190c1-661">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-661">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="190c1-662">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-662">Project</span></span>
- <span data-ttu-id="190c1-663">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-663">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="190c1-664">1 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="190c1-664">February 1, 2019</span></span> 
<span data-ttu-id="190c1-665">Версия 1902 (сборка 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="190c1-665">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="190c1-666">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="190c1-666">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="190c1-667">Word</span><span class="sxs-lookup"><span data-stu-id="190c1-667">Word</span></span> 
- <span data-ttu-id="190c1-668">Устранена проблема с изменением размера ячеек во внедренной таблице Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-668">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="190c1-669">Устранена проблема с копированием и вставкой фигур на полотне</span><span class="sxs-lookup"><span data-stu-id="190c1-669">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="190c1-670">Excel</span><span class="sxs-lookup"><span data-stu-id="190c1-670">Excel</span></span>
- <span data-ttu-id="190c1-671">Исправлена ошибка с открытием файлов из Excel Web App</span><span class="sxs-lookup"><span data-stu-id="190c1-671">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="190c1-672">Исправлена ошибка, вызывавшая сбой при сохранении CSV-файла в формате XLSX из-за длины имени файла</span><span class="sxs-lookup"><span data-stu-id="190c1-672">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="190c1-673">Исправлено контекстное меню для отображения параметров контекстного меню</span><span class="sxs-lookup"><span data-stu-id="190c1-673">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="190c1-674">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="190c1-674">PowerPoint</span></span>
- <span data-ttu-id="190c1-675">Устранена проблема, из-за которой пользователи не могли использовать сочетания клавиш CTRL+ALT+7 и CTRL+ALT+8 для ввода квадратных скобок</span><span class="sxs-lookup"><span data-stu-id="190c1-675">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="190c1-676">Исправлена ошибка, из-за которой при вставке локального видео в файл PPT уменьшалось место на диске "C"</span><span class="sxs-lookup"><span data-stu-id="190c1-676">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="190c1-677">Исправлена кнопка "Публикация в Microsoft Stream", не отображавшаяся у некоторых пользователей</span><span class="sxs-lookup"><span data-stu-id="190c1-677">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="190c1-678">Outlook</span><span class="sxs-lookup"><span data-stu-id="190c1-678">Outlook</span></span>
- <span data-ttu-id="190c1-679">Исправлена ошибка, из-за которой в представлении задач в календаре неправильно отображалась тема задачи.</span><span class="sxs-lookup"><span data-stu-id="190c1-679">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="190c1-680">Access</span><span class="sxs-lookup"><span data-stu-id="190c1-680">Access</span></span>
- <span data-ttu-id="190c1-681">Исправлена проблема с масштабированием диаграмм</span><span class="sxs-lookup"><span data-stu-id="190c1-681">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="190c1-682">Project</span><span class="sxs-lookup"><span data-stu-id="190c1-682">Project</span></span>
- <span data-ttu-id="190c1-683">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="190c1-683">Various performance and stability fixes</span></span>
