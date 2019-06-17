---
title: Заметки о выпуске для участников программы предварительной оценки Office
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 6/14/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с ранним доступом последний список ключевых новых функций, исправлений или известных проблем
ms.openlocfilehash: 8a2bf54f60b7d35a0f3b2f023e0100ff65d09ed2
ms.sourcegitcommit: 288bea365b4c0265fb9ff182b19ff4eb30b4c7d7
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/14/2019
ms.locfileid: "34948795"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="85f0c-103">Заметки о выпуске для участников программы предварительной оценки Office</span><span class="sxs-lookup"><span data-stu-id="85f0c-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="85f0c-104">Эта статья содержит заметки о выпуске для сборок приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows, предоставляемых в рамках программы предварительной оценки.</span><span class="sxs-lookup"><span data-stu-id="85f0c-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="85f0c-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="85f0c-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="85f0c-106">Обратите внимание на то, что развертывание возможностей (а иногда даже исправлений) для участников программы предварительной оценки зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="85f0c-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="85f0c-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="85f0c-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="85f0c-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="85f0c-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="85f0c-109">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок</span><span class="sxs-lookup"><span data-stu-id="85f0c-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="85f0c-110">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки</span><span class="sxs-lookup"><span data-stu-id="85f0c-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="85f0c-111">Microsoft Teams для существующих установок Office 365 профессиональный плюс — с конца июня Microsoft Teams будет добавляться в существующие установки Office 365 профессиональный плюс (и Office 365 бизнес) при обновлении этих установок.</span><span class="sxs-lookup"><span data-stu-id="85f0c-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="85f0c-112">Дата добавления приложения Teams зависит от используемого канала обновления.</span><span class="sxs-lookup"><span data-stu-id="85f0c-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="85f0c-113">Дополнительные сведения см. в статье [Развертывание Microsoft Teams с Office 365 профессиональный плюс](https://docs.microsoft.com/ru-RU/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="85f0c-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-14-2019"></a><span data-ttu-id="85f0c-114">14 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-114">June 14, 2019</span></span>
<span data-ttu-id="85f0c-115">Версия 1907 (сборка 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="85f0c-115">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-116">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-116">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-117">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-117">Word</span></span> 
- <span data-ttu-id="85f0c-118">Исправлена проблема, которая могла препятствовать входу пользователя при сохранении в OneDrive</span><span class="sxs-lookup"><span data-stu-id="85f0c-118">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="85f0c-119">Исправлена проблема, из-за которой пользователю могло быть запрещено изменять свойства SharePoint в режиме ограниченного доступа</span><span class="sxs-lookup"><span data-stu-id="85f0c-119">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="85f0c-120">Исправлена проблема, из-за которой содержимое колонтитулов могло меняться при изменении полей</span><span class="sxs-lookup"><span data-stu-id="85f0c-120">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="85f0c-121">Исправлена проблема, из-за которой форматирование могло разрываться при переходе в веб-представление</span><span class="sxs-lookup"><span data-stu-id="85f0c-121">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="85f0c-122">Исправлена проблема, которая могла помешать пользователю использовать настраиваемые поля при открытии из SharePoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-122">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-123">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-123">Excel</span></span>
- <span data-ttu-id="85f0c-124">Исправлена проблема с производительностью при удалении строк отфильтрованного набора</span><span class="sxs-lookup"><span data-stu-id="85f0c-124">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="85f0c-125">Исправлена проблема, которая могла иногда вызывать мерцание указателя мыши в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="85f0c-125">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="85f0c-126">Устранена проблема, которая могла приводить к сбою при удалении ряда</span><span class="sxs-lookup"><span data-stu-id="85f0c-126">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="85f0c-127">Исправлена проблема, из-за которой некоторым пользователям предоставлялась возможность добавить журнал версий, когда он недоступен</span><span class="sxs-lookup"><span data-stu-id="85f0c-127">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="85f0c-128">Исправлена проблема, которая могла приводить к возникновению исключения при использовании средства сравнения электронных таблиц</span><span class="sxs-lookup"><span data-stu-id="85f0c-128">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-129">PowerPoint</span></span>
- <span data-ttu-id="85f0c-130">Устранена проблема, из-за которой мог происходить сбой при переходе по ссылке к SharePoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-130">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="85f0c-131">Исправлена проблема, из-за которой пользователь мог переключаться на следующую страницу при вводе с помощью ручки Surface</span><span class="sxs-lookup"><span data-stu-id="85f0c-131">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-132">Outlook</span></span>
- <span data-ttu-id="85f0c-133">Исправлена проблема, из-за которой в некоторых случаях поле "Кому" отображалось увеличенным</span><span class="sxs-lookup"><span data-stu-id="85f0c-133">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-134">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-134">Access</span></span>
- <span data-ttu-id="85f0c-135">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-135">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-136">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-136">Project</span></span>
- <span data-ttu-id="85f0c-137">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-137">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="85f0c-138">7 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-138">June 7, 2019</span></span>
<span data-ttu-id="85f0c-139">Версия 1907 (сборка 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="85f0c-139">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-140">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-140">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-141">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-141">Word</span></span> 
- <span data-ttu-id="85f0c-142">Исправлена проблема, из-за которой возникал сбой в работе Word при автозамене первой буквы предложения на прописную</span><span class="sxs-lookup"><span data-stu-id="85f0c-142">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="85f0c-143">Улучшена производительность при редактировании документа в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="85f0c-143">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="85f0c-144">Исправлена проблема, из-за которой неправильно отображались векторные изображения, созданные в Adobe Illustrator</span><span class="sxs-lookup"><span data-stu-id="85f0c-144">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-145">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-145">Excel</span></span>
- <span data-ttu-id="85f0c-146">Исправлена проблема, из-за которой поля сортировки могли быть неправильно установлены при записи макроса</span><span class="sxs-lookup"><span data-stu-id="85f0c-146">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="85f0c-147">Исправлена проблема, приводящая к зависанию или сбою при пересчете формулы массива</span><span class="sxs-lookup"><span data-stu-id="85f0c-147">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-148">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-148">PowerPoint</span></span>
- <span data-ttu-id="85f0c-149">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-149">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-150">Outlook</span></span>
- <span data-ttu-id="85f0c-151">Исправлена проблема, из-за которой встроенные вложения иногда имели неправильный масштаб</span><span class="sxs-lookup"><span data-stu-id="85f0c-151">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-152">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-152">Access</span></span>
- <span data-ttu-id="85f0c-153">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-153">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-154">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-154">Project</span></span>
- <span data-ttu-id="85f0c-155">Исправлена проблема, из-за которой в расписании заданий с фиксированной длительностью может изменяться дата окончания</span><span class="sxs-lookup"><span data-stu-id="85f0c-155">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="85f0c-156">Исправлена проблема, из-за которой могло неправильно отображаться значение процента выполнения при открытии проекта из более ранней версии</span><span class="sxs-lookup"><span data-stu-id="85f0c-156">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="85f0c-157">31 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-157">May 31, 2019</span></span>
<span data-ttu-id="85f0c-158">Версия 1906 (сборка 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="85f0c-158">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-159">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-159">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-160">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="85f0c-161">Диалоговое окно обращения в службу поддержки теперь закрепляется и отображается справа</span><span class="sxs-lookup"><span data-stu-id="85f0c-161">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="85f0c-162">Диалоговое окно, используемое для обращения в службу поддержки, отображается в области справа и выводится как закрепленное окно.</span><span class="sxs-lookup"><span data-stu-id="85f0c-162">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="85f0c-163">Рукописный ввод в вашем электронном письме!</span><span class="sxs-lookup"><span data-stu-id="85f0c-163">Ink in Your Email!</span></span>

<span data-ttu-id="85f0c-164">В сообщениях электронной почты Outlook теперь можно рисовать и создавать примечания к изображениям.</span><span class="sxs-lookup"><span data-stu-id="85f0c-164">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-165">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-165">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="85f0c-166">Открытие ссылок на документы в Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-166">Open document links in Word</span></span>

<span data-ttu-id="85f0c-167">При переходе по ссылке на документ в Office вы можете изменить параметр, чтобы открывать его в приложении Word по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-167">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="85f0c-168">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="85f0c-168">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="85f0c-169">Подробнее: https://support.office.com/ru-RU/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="85f0c-169">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-170">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-170">Getting Started:</span></span>

<span data-ttu-id="85f0c-171">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-171">Feature will default to off.</span></span> <span data-ttu-id="85f0c-172">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="85f0c-172">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="85f0c-173">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-173">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="85f0c-174">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="85f0c-174">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="85f0c-175">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="85f0c-175">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="85f0c-176">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="85f0c-176">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-177">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-177">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-178">Чтобы запустить интерфейс согласия на открытие ссылки на документ Word, хранящийся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="85f0c-178">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="85f0c-179">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="85f0c-179">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-180">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="85f0c-181">Открытие ссылок на презентации в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-181">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="85f0c-182">При переходе по ссылке на презентацию в Office вы можете изменить параметр, чтобы открывать ее в приложении PowerPoint по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-182">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="85f0c-183">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="85f0c-183">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="85f0c-184">Подробнее: https://support.office.com/ru-RU/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="85f0c-184">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-185">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-185">Getting Started:</span></span>

<span data-ttu-id="85f0c-186">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-186">Feature will default to off.</span></span> <span data-ttu-id="85f0c-187">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="85f0c-187">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="85f0c-188">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-188">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="85f0c-189">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="85f0c-189">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="85f0c-190">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="85f0c-190">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="85f0c-191">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="85f0c-191">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-192">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-192">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-193">Чтобы запустить интерфейс согласия на открытие ссылки на презентацию PowerPoint, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="85f0c-193">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="85f0c-194">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="85f0c-194">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-195">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-195">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="85f0c-196">Открытие ссылок на книги в Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-196">Open workbook links in Excel</span></span>

<span data-ttu-id="85f0c-197">При переходе по ссылке на книгу в Office вы можете изменить параметр, чтобы открывать ее в приложении Excel по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-197">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="85f0c-198">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="85f0c-198">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="85f0c-199">Подробнее: https://support.office.com/ru-RU/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="85f0c-199">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-200">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-200">Getting Started:</span></span>

<span data-ttu-id="85f0c-201">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-201">Feature will default to off.</span></span> <span data-ttu-id="85f0c-202">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="85f0c-202">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="85f0c-203">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="85f0c-203">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="85f0c-204">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="85f0c-204">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="85f0c-205">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="85f0c-205">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="85f0c-206">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="85f0c-206">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-207">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-207">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-208">Чтобы запустить интерфейс согласия на открытие ссылки на книгу Excel, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="85f0c-208">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="85f0c-209">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="85f0c-209">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-210">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-210">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="85f0c-211">Все</span><span class="sxs-lookup"><span data-stu-id="85f0c-211">All</span></span>
- <span data-ttu-id="85f0c-212">Исправлена проблема, из-за которой файлы иногда автоматически сохранялись даже при отключенной функции автоматического сохранения.</span><span class="sxs-lookup"><span data-stu-id="85f0c-212">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-213">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-213">Word</span></span> 
- <span data-ttu-id="85f0c-214">Исправлена ошибка, которая могла не позволять некоторым пользователям сохранять файлы в SharePoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-214">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-215">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-215">Excel</span></span>
- <span data-ttu-id="85f0c-216">Исправлена проблема с возможным отображением неправильного значка для неактивных фильтров</span><span class="sxs-lookup"><span data-stu-id="85f0c-216">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-217">PowerPoint</span></span>
- <span data-ttu-id="85f0c-218">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-218">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-219">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-219">Outlook</span></span>
- <span data-ttu-id="85f0c-220">Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span><span class="sxs-lookup"><span data-stu-id="85f0c-220">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="85f0c-221">Исправлена проблема, не позволявшая функции безопасных ссылок анализировать URL-адрес с конечным пробелом</span><span class="sxs-lookup"><span data-stu-id="85f0c-221">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="85f0c-222">Устранена проблема, из-за которой помещения отображались доступными за пределами нерабочего времени</span><span class="sxs-lookup"><span data-stu-id="85f0c-222">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-223">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-223">Access</span></span>
- <span data-ttu-id="85f0c-224">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-224">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-225">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-225">Project</span></span>
- <span data-ttu-id="85f0c-226">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-226">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="85f0c-227">24 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-227">May 24, 2019</span></span>
<span data-ttu-id="85f0c-228">Версия 1906 (сборка 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="85f0c-228">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-229">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-229">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="85f0c-230">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="85f0c-230">User Experience Updates</span></span>

<span data-ttu-id="85f0c-231">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="85f0c-231">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-232">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-232">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="85f0c-233">Все</span><span class="sxs-lookup"><span data-stu-id="85f0c-233">All</span></span>

- <span data-ttu-id="85f0c-234">Исправлена проблема, из-за которой не отображалась область чата</span><span class="sxs-lookup"><span data-stu-id="85f0c-234">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-235">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-235">Word</span></span> 
- <span data-ttu-id="85f0c-236">Исправлена проблема, из-за которой в некоторых случаях приложение Word могло неправильно выделять текст на наличие грамматических ошибок</span><span class="sxs-lookup"><span data-stu-id="85f0c-236">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-237">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-237">Excel</span></span>
- <span data-ttu-id="85f0c-238">Исправлена проблема, из-за которой применялся неправильный значок для элементов диаграммы</span><span class="sxs-lookup"><span data-stu-id="85f0c-238">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="85f0c-239">Исправлена проблема, приводившая к активации неверной книги в скрипте VBA, если эта книга уже открыта</span><span class="sxs-lookup"><span data-stu-id="85f0c-239">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-240">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-240">PowerPoint</span></span>
- <span data-ttu-id="85f0c-241">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-241">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-242">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-242">Outlook</span></span>
- <span data-ttu-id="85f0c-243">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-243">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-244">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-244">Access</span></span>
- <span data-ttu-id="85f0c-245">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-245">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-246">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-246">Project</span></span>
- <span data-ttu-id="85f0c-247">Устранена ошибка, при которой приложение Project аварийно завершало работу после перехода на панель задач</span><span class="sxs-lookup"><span data-stu-id="85f0c-247">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="85f0c-248">17 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-248">May 17, 2019</span></span>
<span data-ttu-id="85f0c-249">Версия 1906 (сборка 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="85f0c-249">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-250">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-250">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-251">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-251">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="85f0c-252">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="85f0c-252">User Experience Updates</span></span>

<span data-ttu-id="85f0c-253">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="85f0c-253">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-254">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-254">Getting Started:</span></span>

<span data-ttu-id="85f0c-255">Эти изменения относятся к новому стандартному пользовательскому интерфейсу; он был доступен с помощью переключателя "Ожидается в ближайшее время" с середины декабря для 100 % рабочих сред</span><span class="sxs-lookup"><span data-stu-id="85f0c-255">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="85f0c-256">Настраиваемая упрощенная лента</span><span class="sxs-lookup"><span data-stu-id="85f0c-256">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="85f0c-257">Возможность простой настройки для переключения между классическим и упрощенным представлением, а также для закрепления и открепления команд.</span><span class="sxs-lookup"><span data-stu-id="85f0c-257">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-258">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-258">Getting Started:</span></span>

<span data-ttu-id="85f0c-259">Пользователи могут перейти к упрощенной ленте, включив переключатель "Ожидается в ближайшее время" (изначально) и щелкнув шеврон на ленте, чтобы переключаться между классической многострочной и новой упрощенной однострочной лентой.</span><span class="sxs-lookup"><span data-stu-id="85f0c-259">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-260">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-260">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-261">Переключение с классической на упрощенную ленту</span><span class="sxs-lookup"><span data-stu-id="85f0c-261">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="85f0c-262">Выбор избранного действия</span><span class="sxs-lookup"><span data-stu-id="85f0c-262">Pick your favorite action</span></span>

<span data-ttu-id="85f0c-263">Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="85f0c-263">Don't use Flag and Delete?</span></span> <span data-ttu-id="85f0c-264">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="85f0c-264">How about Archive or Mark as Read?</span></span> <span data-ttu-id="85f0c-265">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="85f0c-265">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-266">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-266">Getting Started:</span></span>

<span data-ttu-id="85f0c-267">Чтобы выбрать быстрые действия, щелкните правой кнопкой мыши сообщение в списке для отображения контекстного меню.</span><span class="sxs-lookup"><span data-stu-id="85f0c-267">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="85f0c-268">Затем выберите пункт "Задать быстрые действия"</span><span class="sxs-lookup"><span data-stu-id="85f0c-268">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-269">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-269">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-270">Изменение используемых по умолчанию действий "Пометить" и "Удалить" на "Архивировать", "Переместить", "Пометить как прочитанные" или "Отсутствует" для уменьшения элементов в списке сообщений</span><span class="sxs-lookup"><span data-stu-id="85f0c-270">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="85f0c-271">Самостоятельно</span><span class="sxs-lookup"><span data-stu-id="85f0c-271">Relaxed or tighter layout?</span></span> <span data-ttu-id="85f0c-272">выбирайте свободный или компактный макет</span><span class="sxs-lookup"><span data-stu-id="85f0c-272">You choose</span></span>

<span data-ttu-id="85f0c-273">С помощью компактных интервалов можно выбрать дополнительное пространство между элементами или более сжатый макет, чтобы увидеть больше элементов.</span><span class="sxs-lookup"><span data-stu-id="85f0c-273">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-274">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-274">Getting Started:</span></span>

<span data-ttu-id="85f0c-275">Вкладка "Вид", флажок "Уменьшить интервал" в группе "Сообщения" для классической ленты и параметры текущего представления для упрощенной ленты</span><span class="sxs-lookup"><span data-stu-id="85f0c-275">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-276">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-276">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-277">Использование Outlook для просмотра и создания сообщений с включенным и отключенным параметром.</span><span class="sxs-lookup"><span data-stu-id="85f0c-277">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="85f0c-278">При включенном параметре "Уменьшить интервал" на странице располагается больше сообщений, а элементы управления в формах создания упрощаются.</span><span class="sxs-lookup"><span data-stu-id="85f0c-278">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="85f0c-279">Дедупликация недавно использовавшихся записей при применении клиента синхронизации OneDrive</span><span class="sxs-lookup"><span data-stu-id="85f0c-279">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="85f0c-280">Улучшите интеграцию с клиентом синхронизации OneDrive с помощью облачных вложений, выполнив дедупликацмию недавно использовавшихся записей, обеспечивающую ускорение вложения в виде копии для синхронизированных данных</span><span class="sxs-lookup"><span data-stu-id="85f0c-280">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-281">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-281">Getting Started:</span></span>

<span data-ttu-id="85f0c-282">При использовании клиента синхронизации OneDrive дубликаты больше не отображаются в меню последних выбиравшихся для вложений файлов.</span><span class="sxs-lookup"><span data-stu-id="85f0c-282">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-283">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-283">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-284">Включение клиента синхронизации OneDrive и использование меню "Вложить файл" в классической версии Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-284">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="85f0c-285">Улучшенная синхронизация общих папок для почтовых ящиков с большим числом папок</span><span class="sxs-lookup"><span data-stu-id="85f0c-285">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="85f0c-286">В течение нескольких лет при синхронизации общих почтовых ящиков в приложении Outlook существовало ограничение не более 500 папок.</span><span class="sxs-lookup"><span data-stu-id="85f0c-286">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="85f0c-287">В результате этого изменения при синхронизации в Outlook больше не будет применяться это ограничение в 500 папок.</span><span class="sxs-lookup"><span data-stu-id="85f0c-287">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-288">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-288">Getting Started:</span></span>

<span data-ttu-id="85f0c-289">Создайте в почтовом ящике 1000 папок, предоставьте другому пользователю доступ к почтовому ящику, создайте профиль Outlook для "другого пользователя" и убедитесь в выполнении синхронизации.</span><span class="sxs-lookup"><span data-stu-id="85f0c-289">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-290">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-290">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="85f0c-291">Стереть лишь небольшую часть</span><span class="sxs-lookup"><span data-stu-id="85f0c-291">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-292">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-292">Getting Started:</span></span>

<span data-ttu-id="85f0c-293">Откройте вкладку "Рисование". Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="85f0c-293">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="85f0c-294">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="85f0c-294">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-295">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-295">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-296">Откройте вкладку "Рисование". Выберите перо.</span><span class="sxs-lookup"><span data-stu-id="85f0c-296">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="85f0c-297">Нанесите росчерк пером.</span><span class="sxs-lookup"><span data-stu-id="85f0c-297">Draw an ink stroke.</span></span> <span data-ttu-id="85f0c-298">Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="85f0c-298">Select the Eraser dropdown.</span></span> <span data-ttu-id="85f0c-299">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="85f0c-299">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="85f0c-300">Сотрите лишь небольшую часть росчерка пера.</span><span class="sxs-lookup"><span data-stu-id="85f0c-300">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-301">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-301">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="85f0c-302">Все</span><span class="sxs-lookup"><span data-stu-id="85f0c-302">All</span></span> 
- <span data-ttu-id="85f0c-303">Исправлена проблема, из-за которой некоторым пользователям могло не удаваться сохранять файлы в формате PDF</span><span class="sxs-lookup"><span data-stu-id="85f0c-303">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="85f0c-304">Исправлена проблема, которая могла влиять на сохранение пользователями больших файлов в 32-разрядной системе</span><span class="sxs-lookup"><span data-stu-id="85f0c-304">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-305">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-305">Word</span></span> 
- <span data-ttu-id="85f0c-306">Значительно повышена скорость реагирования функции диктовки</span><span class="sxs-lookup"><span data-stu-id="85f0c-306">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-307">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-307">Excel</span></span>
- <span data-ttu-id="85f0c-308">Исправлена проблема, из-за которой события двойного щелчка могли не срабатывать на устройствах с сенсорным экраном</span><span class="sxs-lookup"><span data-stu-id="85f0c-308">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="85f0c-309">Исправлена проблема, которая могла блокировать для некоторых пользователей редактирование макросов VBA</span><span class="sxs-lookup"><span data-stu-id="85f0c-309">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="85f0c-310">Исправлена проблема, которая могла влиять на производительность при использовании срезов</span><span class="sxs-lookup"><span data-stu-id="85f0c-310">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-311">PowerPoint</span></span>
- <span data-ttu-id="85f0c-312">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-312">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-313">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-313">Outlook</span></span>
- <span data-ttu-id="85f0c-314">Исправлена проблема, из-за которой неверный шаблон мог отображаться среди выбранных</span><span class="sxs-lookup"><span data-stu-id="85f0c-314">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-315">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-315">Access</span></span>
- <span data-ttu-id="85f0c-316">Исправлена проблема, из-за которой могло быть затруднено чтение текста при использовании построителя масштаба для отображения длинного форматированного текста</span><span class="sxs-lookup"><span data-stu-id="85f0c-316">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-317">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-317">Project</span></span>
- <span data-ttu-id="85f0c-318">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-318">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="85f0c-319">10 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-319">May 10, 2019</span></span>
<span data-ttu-id="85f0c-320">Версия 1906 (сборка 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="85f0c-320">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-321">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-321">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="85f0c-322">Все</span><span class="sxs-lookup"><span data-stu-id="85f0c-322">All</span></span>
- <span data-ttu-id="85f0c-323">Исправлена проблема, из-за которой диалоговое окно "Сохранить как" могло отображать неправильный путь</span><span class="sxs-lookup"><span data-stu-id="85f0c-323">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-324">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-324">Word</span></span> 
- <span data-ttu-id="85f0c-325">Исправлена проблема, из-за которой не вставлялись некоторые выбранные элементы из области "Что вы хотите сделать?"</span><span class="sxs-lookup"><span data-stu-id="85f0c-325">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-326">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-326">Excel</span></span>
- <span data-ttu-id="85f0c-327">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-327">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-328">PowerPoint</span></span>
- <span data-ttu-id="85f0c-329">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-329">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-330">Outlook</span></span>
- <span data-ttu-id="85f0c-331">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-331">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-332">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-332">Access</span></span>
- <span data-ttu-id="85f0c-333">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-333">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-334">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-334">Project</span></span>
- <span data-ttu-id="85f0c-335">Исправлена проблема, из-за которой могло требоваться выделение для просмотра идентификатора задачи</span><span class="sxs-lookup"><span data-stu-id="85f0c-335">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="85f0c-336">3 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-336">May 3, 2019</span></span>
<span data-ttu-id="85f0c-337">Версия 1906 (сборка 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="85f0c-337">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-338">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-338">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="85f0c-339">Все</span><span class="sxs-lookup"><span data-stu-id="85f0c-339">All</span></span>
- <span data-ttu-id="85f0c-340">Исправлена ошибка, из-за которой у некоторых пользователей возникали проблемы с синхронизацией OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="85f0c-340">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-341">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-341">Word</span></span> 
- <span data-ttu-id="85f0c-342">Исправлена ошибка, из-за которой в некоторых случаях запуск Word занимал много времени</span><span class="sxs-lookup"><span data-stu-id="85f0c-342">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-343">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-343">Excel</span></span>
- <span data-ttu-id="85f0c-344">Исправлена проблема, из-за которой внешние ссылки иногда удалялись из книг после обновления до более новой версии Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-344">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="85f0c-345">Исправлена проблема, из-за которой у некоторых пользователей могли возникать сложности с выделением ячеек в новой книге</span><span class="sxs-lookup"><span data-stu-id="85f0c-345">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-346">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-346">PowerPoint</span></span>
- <span data-ttu-id="85f0c-347">Исправлена проблема, из-за которой при преобразовании рисунков в текст неправильно согласовывались размеры шрифтов</span><span class="sxs-lookup"><span data-stu-id="85f0c-347">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-348">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-348">Outlook</span></span>
- <span data-ttu-id="85f0c-349">Исправлена проблема, из-за которой сохранение контакта из VCF-файла могло привести к получению пустых полей</span><span class="sxs-lookup"><span data-stu-id="85f0c-349">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="85f0c-350">Исправлена проблема, из-за которой сообщение могло оставаться в папке "Исходящие", хотя оно было отправлено</span><span class="sxs-lookup"><span data-stu-id="85f0c-350">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="85f0c-351">Исправлена проблема с аварийным завершением работы Outlook при просмотре сообщения DRM</span><span class="sxs-lookup"><span data-stu-id="85f0c-351">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-352">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-352">Access</span></span>
- <span data-ttu-id="85f0c-353">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-353">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-354">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-354">Project</span></span>
- <span data-ttu-id="85f0c-355">Устранена ошибка, при которой редактор менялся с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="85f0c-355">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="85f0c-356">Устранена проблема, из-за которой неопубликованные задачи могли отображаться в опубликованной копии главного проекта</span><span class="sxs-lookup"><span data-stu-id="85f0c-356">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="85f0c-357">26 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-357">April 26, 2019</span></span>
<span data-ttu-id="85f0c-358">Версия 1905 (сборка 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="85f0c-358">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-359">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-359">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-360">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-360">Word</span></span> 
- <span data-ttu-id="85f0c-361">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-361">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-362">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-362">Excel</span></span>
- <span data-ttu-id="85f0c-363">Устранена проблема, которая приводила к невозможности запуска макросов надстройки "Поиск решения"</span><span class="sxs-lookup"><span data-stu-id="85f0c-363">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="85f0c-364">Устранена проблема, которая могла препятствовать импорту файлов Excel в SharePoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-364">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-365">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-365">PowerPoint</span></span>
- <span data-ttu-id="85f0c-366">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-366">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-367">Outlook</span></span>
- <span data-ttu-id="85f0c-368">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-368">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-369">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-369">Access</span></span>
- <span data-ttu-id="85f0c-370">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-370">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-371">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-371">Project</span></span>
- <span data-ttu-id="85f0c-372">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-372">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="85f0c-373">19 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-373">April 19, 2019</span></span>
<span data-ttu-id="85f0c-374">Версия 1905 (сборка 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="85f0c-374">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-375">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-375">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-376">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-376">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="85f0c-377">Улучшенный интерфейс картограмм с использованием типов данных</span><span class="sxs-lookup"><span data-stu-id="85f0c-377">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="85f0c-378">Эта возможность является улучшением для пользователей, создающих картограммы с использованием географических типов данных Excel.</span><span class="sxs-lookup"><span data-stu-id="85f0c-378">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="85f0c-379">Преимущество для пользователей заключается в более глубокой интеграции функций и повышенной точности в области, которую пользователь хочет отобразить на карте.</span><span class="sxs-lookup"><span data-stu-id="85f0c-379">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="85f0c-380">Дополнительные преимущества включают возможность нанесения на карту многоугольников городов.</span><span class="sxs-lookup"><span data-stu-id="85f0c-380">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="85f0c-381">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-381">Getting Started:</span></span>

- <span data-ttu-id="85f0c-382">Эта возможность является улучшением существующих функций в Excel.</span><span class="sxs-lookup"><span data-stu-id="85f0c-382">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="85f0c-383">Чтобы использовать улучшение, преобразуйте расположения в объекты Rich и выполните построение с помощью картограмм.</span><span class="sxs-lookup"><span data-stu-id="85f0c-383">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-384">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-384">Scenarios to Try:</span></span>

- <span data-ttu-id="85f0c-385">Пользователи могут попробовать указать на картах города, регионы, районы, страны и почтовые индексы.</span><span class="sxs-lookup"><span data-stu-id="85f0c-385">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="85f0c-386">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-386">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="85f0c-387">Все приложения</span><span class="sxs-lookup"><span data-stu-id="85f0c-387">All Applications</span></span>
- <span data-ttu-id="85f0c-388">Исправлена ошибка, из-за которой диалоговое окно первого запуска отображалось при каждом запуске приложения</span><span class="sxs-lookup"><span data-stu-id="85f0c-388">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="85f0c-389">Исправлена ошибка с возможным отсутствием ссылки SharePoint в диалоговом окне "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="85f0c-389">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="85f0c-390">Исправлена ошибка, из-за которой для пользователей неправильно отображалось диалоговое окно "Восстановить"</span><span class="sxs-lookup"><span data-stu-id="85f0c-390">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-391">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-391">Word</span></span> 
- <span data-ttu-id="85f0c-392">Исправлена ошибка, из-за которой у некоторых пользователей могла возникать ошибка с сообщением о недостатке памяти или места на диске при запросе шрифта</span><span class="sxs-lookup"><span data-stu-id="85f0c-392">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="85f0c-393">Исправлена ошибка, из-за которой мог теряться фокус окна при переходе из области примечаний</span><span class="sxs-lookup"><span data-stu-id="85f0c-393">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-394">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-394">Excel</span></span>
- <span data-ttu-id="85f0c-395">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-395">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-396">PowerPoint</span></span>
- <span data-ttu-id="85f0c-397">Исправлена ошибка, не позволявшая изменять размер фигур с фирменной символикой</span><span class="sxs-lookup"><span data-stu-id="85f0c-397">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="85f0c-398">Исправлена ошибка, из-за которой приложение PowerPoint могло аварийно завершать работу при открытии файла в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="85f0c-398">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-399">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-399">Outlook</span></span>
- <span data-ttu-id="85f0c-400">Исправлена ошибка, не позволявшая некоторым пользователям выделять китайские слова</span><span class="sxs-lookup"><span data-stu-id="85f0c-400">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="85f0c-401">Исправлена ошибка с неправильным вычислением сроков действия</span><span class="sxs-lookup"><span data-stu-id="85f0c-401">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-402">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-402">Access</span></span>
- <span data-ttu-id="85f0c-403">Исправлена ошибка, не позволявшая некоторым пользователям применять построитель макросов</span><span class="sxs-lookup"><span data-stu-id="85f0c-403">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="85f0c-404">Исправлена ошибка, из-за которой при печати отчета печаталась только первая страница</span><span class="sxs-lookup"><span data-stu-id="85f0c-404">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="85f0c-405">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при наведении указателя на гиперссылку</span><span class="sxs-lookup"><span data-stu-id="85f0c-405">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="85f0c-406">Исправлена проблема, приводившая к отображению некоторых элементов вне экрана при использовании представления "Схема данных"</span><span class="sxs-lookup"><span data-stu-id="85f0c-406">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-407">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-407">Project</span></span>
- <span data-ttu-id="85f0c-408">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-408">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="85f0c-409">12 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-409">April 12, 2019</span></span>
<span data-ttu-id="85f0c-410">Версия 1905 (сборка 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="85f0c-410">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-411">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-411">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-412">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-412">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="85f0c-413">Новая возможность в Access: соединитель данных с Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="85f0c-413">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="85f0c-414">Связывайтесь со службами Microsoft Graph или импортируйте из них данные, чтобы создавать приложения, использующие интеллектуальные контекстные данные, хранящиеся в Graph</span><span class="sxs-lookup"><span data-stu-id="85f0c-414">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-415">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-415">Getting Started:</span></span>

<span data-ttu-id="85f0c-416">На вкладке ленты "Внешние данные" нажмите кнопку "Создать источник данных" и найдите новый соединитель Graph в меню "Из Online Services".</span><span class="sxs-lookup"><span data-stu-id="85f0c-416">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-417">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-417">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-418">Импорт из различных служб Graph или связывание с ними, включая службы "Люди", "Группы" и "Элементы OneDrive".</span><span class="sxs-lookup"><span data-stu-id="85f0c-418">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-419">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-419">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="85f0c-420">Все приложения</span><span class="sxs-lookup"><span data-stu-id="85f0c-420">All Applications</span></span>
 - <span data-ttu-id="85f0c-421">Исправлена ошибка, не позволявшая некоторым пользователям сохранять файлы в облачных расположениях</span><span class="sxs-lookup"><span data-stu-id="85f0c-421">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="85f0c-422">Исправлена ошибка, из-за которой могла открываться неправильная область из ленты</span><span class="sxs-lookup"><span data-stu-id="85f0c-422">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-423">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-423">Word</span></span> 
- <span data-ttu-id="85f0c-424">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-424">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-425">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-425">Excel</span></span>
- <span data-ttu-id="85f0c-426">Исправлена ошибка, из-за которой для пользователей отображалось сообщение об ошибке, относящееся к связанным типам данных, если книга не содержала связанные типы данных</span><span class="sxs-lookup"><span data-stu-id="85f0c-426">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="85f0c-427">Исправлена ошибка, из-за которой URL-ссылки в документе Word могли изменяться в зависимости от способа просмотра (локально или в Интернете)</span><span class="sxs-lookup"><span data-stu-id="85f0c-427">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-428">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-428">PowerPoint</span></span>
- <span data-ttu-id="85f0c-429">Исправлена ошибка, из-за которой мог происходить сбой приложения после отмены всех изменений на вкладке "Анимация"</span><span class="sxs-lookup"><span data-stu-id="85f0c-429">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-430">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-430">Outlook</span></span>
- <span data-ttu-id="85f0c-431">Исправлена ошибка, не позволявшая некоторым пользователям изменять поле "Заметки" для контактов в общедоступной папке</span><span class="sxs-lookup"><span data-stu-id="85f0c-431">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="85f0c-432">Исправлена ошибка, из-за которой мог возникать конфликт между датами окончания срока действия и датами удаления</span><span class="sxs-lookup"><span data-stu-id="85f0c-432">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-433">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-433">Access</span></span>
- <span data-ttu-id="85f0c-434">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-434">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-435">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-435">Project</span></span>
- <span data-ttu-id="85f0c-436">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-436">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="85f0c-437">5 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-437">April 5, 2019</span></span>
<span data-ttu-id="85f0c-438">Версия 1904 (сборка 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="85f0c-438">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-439">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-439">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-440">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="85f0c-441">Outlook для Windows: настройка параметров сортировки почты и предоставление к ним общего доступа</span><span class="sxs-lookup"><span data-stu-id="85f0c-441">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="85f0c-442">Ваши параметры сортировки почты хранятся в облаке, поэтому можно наслаждаться единообразным интерфейсом при использовании Outlook для Windows и Outlook в Интернете с любого устройства.</span><span class="sxs-lookup"><span data-stu-id="85f0c-442">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-443">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-443">Getting Started:</span></span>

<span data-ttu-id="85f0c-444">На вкладке "Общие" в разделе "Файл" > "Параметры" есть новый параметр "Хранить мои параметры Outlook в облаке".</span><span class="sxs-lookup"><span data-stu-id="85f0c-444">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="85f0c-445">Пользователям нужно установить флажок, чтобы разрешить перенос параметра сортировки почты в другие экземпляры классической версии Outlook и Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="85f0c-445">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-446">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-446">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-447">Измените сортировку почты на компьютере с включенными облачными параметрами.</span><span class="sxs-lookup"><span data-stu-id="85f0c-447">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="85f0c-448">Перейдите в Outlook Web App и убедитесь, что этот параметр также применен.</span><span class="sxs-lookup"><span data-stu-id="85f0c-448">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="85f0c-449">Измените настройки сортировки почты в Outlook Web App и запустите классическую версию Outlook, чтобы увидеть применение этих настроек.</span><span class="sxs-lookup"><span data-stu-id="85f0c-449">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-450">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-450">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="85f0c-451">В режиме "Средства обучения" реализована поддержка дополнительных цветов страниц</span><span class="sxs-lookup"><span data-stu-id="85f0c-451">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="85f0c-452">Средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="85f0c-452">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="85f0c-453">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="85f0c-453">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-454">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-454">Getting Started:</span></span>

<span data-ttu-id="85f0c-455">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="85f0c-455">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-456">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-456">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-457">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="85f0c-457">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-458">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-458">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="85f0c-459">Расширение возможностей для творчества с помощью анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="85f0c-459">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="85f0c-460">Теперь Office поддерживает анимированные модели, воспроизводимые в редакторе, чтобы вы могли оживить свои листы!</span><span class="sxs-lookup"><span data-stu-id="85f0c-460">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-461">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-461">Getting Started:</span></span>

1. <span data-ttu-id="85f0c-462">Откройте Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-462">Open Excel.</span></span>
2. <span data-ttu-id="85f0c-463">Вставьте анимированную трехмерную модель (вскоре будут доступны в сообществе Remix, а пока их можно найти здесь: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="85f0c-463">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="85f0c-464">Анимированная модель будет воспроизводиться в редакторе!</span><span class="sxs-lookup"><span data-stu-id="85f0c-464">The animated model will play in the editor!</span></span> <span data-ttu-id="85f0c-465">Проверьте режим слайд-шоу, она будет воспроизводиться и там!</span><span class="sxs-lookup"><span data-stu-id="85f0c-465">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="85f0c-466">На ленте форматирования трехмерных моделей можно ознакомиться с дополнительными анимационными сценами в модели</span><span class="sxs-lookup"><span data-stu-id="85f0c-466">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-467">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-467">Scenarios to Try:</span></span>

1. <span data-ttu-id="85f0c-468">Вставьте анимированную модель и посмотрите, как она будет воспроизводиться в редакторе</span><span class="sxs-lookup"><span data-stu-id="85f0c-468">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="85f0c-469">Узнайте, какие анимационные сцены доступны для анимированной модели в коллекции "Сцены" на ленте форматирования трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="85f0c-469">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="85f0c-470">Можно воспроизводить или приостанавливать анимацию с помощью ленты, мини-панели или клавиши ПРОБЕЛ.</span><span class="sxs-lookup"><span data-stu-id="85f0c-470">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-471">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-471">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="85f0c-472">Все приложения</span><span class="sxs-lookup"><span data-stu-id="85f0c-472">All Applications</span></span>
- <span data-ttu-id="85f0c-473">Мы исправили ошибку, когда значок приложения для Excel может отображаться неправильно в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="85f0c-473">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="85f0c-474">Мы исправили ошибку, когда после установки обновления может исчезать кнопка меню "Файл".</span><span class="sxs-lookup"><span data-stu-id="85f0c-474">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="85f0c-475">Исправлена проблема, в результате которой может измениться пользовательская лицензия.</span><span class="sxs-lookup"><span data-stu-id="85f0c-475">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-476">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-476">Word</span></span> 
- <span data-ttu-id="85f0c-477">Исправлена проблема с неправильным отображением текста при определенных уровнях масштабирования.</span><span class="sxs-lookup"><span data-stu-id="85f0c-477">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-478">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-478">Excel</span></span>
- <span data-ttu-id="85f0c-479">Мы исправили ошибку, в результате которой пользователи могли не видеть запрос на сохранение книги после внесения изменений.</span><span class="sxs-lookup"><span data-stu-id="85f0c-479">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="85f0c-480">Мы исправили ошибку, когда событие BeforeSave не запускалось, если пользователь предоставил общий доступ к книге.</span><span class="sxs-lookup"><span data-stu-id="85f0c-480">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="85f0c-481">Исправлена проблема, когда изменение размера столбца на менее чем 6 пикселей вызывает появление сообщения об ошибке.</span><span class="sxs-lookup"><span data-stu-id="85f0c-481">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="85f0c-482">Исправлена ошибка, когда Excel игнорирует метку Application.Visible.</span><span class="sxs-lookup"><span data-stu-id="85f0c-482">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="85f0c-483">Исправлена ошибка, когда стрелки трассировки остаются на неактивных закрепленных областях.</span><span class="sxs-lookup"><span data-stu-id="85f0c-483">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="85f0c-484">Исправлена ошибка, когда форматирование ячеек дат и валют может изменяться при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="85f0c-484">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="85f0c-485">Мы исправили ошибку, когда подсказки могли неожиданно перемещаться</span><span class="sxs-lookup"><span data-stu-id="85f0c-485">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="85f0c-486">Мы исправили ошибки локализации редактора Power Query</span><span class="sxs-lookup"><span data-stu-id="85f0c-486">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="85f0c-487">Мы устранили проблему, когда рабочая книга могла удаляться из вложений при отправке по электронной почте.</span><span class="sxs-lookup"><span data-stu-id="85f0c-487">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-488">PowerPoint</span></span>
- <span data-ttu-id="85f0c-489">Мы устранили проблему с длительным временем, которое может требоваться на копирование форм.</span><span class="sxs-lookup"><span data-stu-id="85f0c-489">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-490">Outlook</span></span>
- <span data-ttu-id="85f0c-491">Мы устранили проблему с аварийным завершением работы Outlook при использовании инструмента рисования</span><span class="sxs-lookup"><span data-stu-id="85f0c-491">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="85f0c-492">Устранена проблема локализации при составлении HTML-сообщений электронной почты</span><span class="sxs-lookup"><span data-stu-id="85f0c-492">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="85f0c-493">Мы устранили проблему, когда пользователи сталкивались с трудностями при выборе нижней панели</span><span class="sxs-lookup"><span data-stu-id="85f0c-493">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-494">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-494">Access</span></span>
- <span data-ttu-id="85f0c-495">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-495">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-496">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-496">Project</span></span>
- <span data-ttu-id="85f0c-497">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-497">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="85f0c-498">22 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-498">March 22, 2019</span></span>
<span data-ttu-id="85f0c-499">Версия 1904 (сборка 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="85f0c-499">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-500">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-500">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-501">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-501">Word</span></span> 
- <span data-ttu-id="85f0c-502">Устранена ошибка, при которой в интерфейсе пользователя постоянно отображается "Проверка изменений".</span><span class="sxs-lookup"><span data-stu-id="85f0c-502">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-503">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-503">Excel</span></span>
- <span data-ttu-id="85f0c-504">Устранена ошибка, при которой приложение аварийно завершало работу после перемещения листа</span><span class="sxs-lookup"><span data-stu-id="85f0c-504">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="85f0c-505">Устранена ошибка, при которой приложение аварийно завершало работу после сохранения в формате PDF</span><span class="sxs-lookup"><span data-stu-id="85f0c-505">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="85f0c-506">Устранена ошибка, при которой диалоговое окно сохранения не воспринимало некоторые корейские символы</span><span class="sxs-lookup"><span data-stu-id="85f0c-506">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-507">PowerPoint</span></span>
- <span data-ttu-id="85f0c-508">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-508">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-509">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-509">Outlook</span></span>
- <span data-ttu-id="85f0c-510">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-510">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-511">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-511">Access</span></span>
- <span data-ttu-id="85f0c-512">Исправлено сообщение об ошибке в Access, при которой создавался дополнительный ярлык для Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-512">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="85f0c-513">Устранена ошибка, при которой данные со связанного сайта SharePoint отображались неправильно</span><span class="sxs-lookup"><span data-stu-id="85f0c-513">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-514">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-514">Project</span></span>
- <span data-ttu-id="85f0c-515">Устранена ошибка, при которой языковые параметры менялись с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="85f0c-515">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="85f0c-516">Устранена ошибка, при которой приложение аварийно завершало работу при синхронизации с SharePoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-516">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="85f0c-517">15 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-517">March 15, 2019</span></span>
<span data-ttu-id="85f0c-518">Версия 1904 (сборка 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="85f0c-518">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-519">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-519">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-520">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-520">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="85f0c-521">Режим фокусировки</span><span class="sxs-lookup"><span data-stu-id="85f0c-521">Focus mode</span></span>

<span data-ttu-id="85f0c-522">Хотите, чтобы вас ничего не отвлекало от работы? Переключитесь в режим фокусировки в меню "Вид".</span><span class="sxs-lookup"><span data-stu-id="85f0c-522">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="85f0c-523">Только для обладателей подписки на Office 365.</span><span class="sxs-lookup"><span data-stu-id="85f0c-523">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-524">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-524">Getting Started:</span></span>

<span data-ttu-id="85f0c-525">Кнопка "Фокус" вкладки "Вид" в строке состояния ленты с кнопкой "Фокус"</span><span class="sxs-lookup"><span data-stu-id="85f0c-525">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-526">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-526">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-527">Переход в режим фокусировки и работа в интерфейсе фокусировки</span><span class="sxs-lookup"><span data-stu-id="85f0c-527">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-528">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-528">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-529">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-529">Word</span></span> 
- <span data-ttu-id="85f0c-530">Исправлена проблема, из-за которой изображения в документе, сохраненном в формате PDF, имели неправильное значение точек на дюйм</span><span class="sxs-lookup"><span data-stu-id="85f0c-530">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-531">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-531">Excel</span></span>
- <span data-ttu-id="85f0c-532">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-532">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-533">PowerPoint</span></span>
- <span data-ttu-id="85f0c-534">Исправлена проблема, из-за которой область примечаний открывалась и закрывалась неправильно</span><span class="sxs-lookup"><span data-stu-id="85f0c-534">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="85f0c-535">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при удалении видео</span><span class="sxs-lookup"><span data-stu-id="85f0c-535">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="85f0c-536">Исправлена проблема, когда некоторые экземпляры приложения не запускались.</span><span class="sxs-lookup"><span data-stu-id="85f0c-536">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-537">Outlook</span></span>
- <span data-ttu-id="85f0c-538">Исправлена проблема с неправильными уведомлениями о прочтении при просмотре на японском языке.</span><span class="sxs-lookup"><span data-stu-id="85f0c-538">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-539">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-539">Access</span></span>
- <span data-ttu-id="85f0c-540">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-540">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-541">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-541">Project</span></span>
- <span data-ttu-id="85f0c-542">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-542">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="85f0c-543">8 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-543">March 8, 2019</span></span> 
<span data-ttu-id="85f0c-544">Версия 1903 (сборка 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="85f0c-544">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-545">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-545">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-546">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-546">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="85f0c-547">Находите нужные элементы с помощью Поиска (Майкрософт)</span><span class="sxs-lookup"><span data-stu-id="85f0c-547">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="85f0c-548">С помощью поиска Майкрософт можно найти все файлы, команды и пользователей, которые необходимы для выполнения работы.</span><span class="sxs-lookup"><span data-stu-id="85f0c-548">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-549">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-549">Getting Started:</span></span>

- <span data-ttu-id="85f0c-550">Эта функция выделяется вверху пользовательского интерфейса в заголовке.</span><span class="sxs-lookup"><span data-stu-id="85f0c-550">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-551">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-551">Scenarios to Try:</span></span>

- <span data-ttu-id="85f0c-552">Поиск учебного заведения, недавнего документа или часто используемых команд ленты</span><span class="sxs-lookup"><span data-stu-id="85f0c-552">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="85f0c-553">Поиск статьи или темы и получение дополнительных сведений о ней</span><span class="sxs-lookup"><span data-stu-id="85f0c-553">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="85f0c-554">Совместное редактирование</span><span class="sxs-lookup"><span data-stu-id="85f0c-554">CoAuthoring</span></span>

<span data-ttu-id="85f0c-555">Вам надоело получать блокировку на документы с макросами?</span><span class="sxs-lookup"><span data-stu-id="85f0c-555">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="85f0c-556">Теперь DOCM-файлы в OneDrive для бизнеса поддерживают одновременное редактирование несколькими авторами.</span><span class="sxs-lookup"><span data-stu-id="85f0c-556">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-557">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-557">Getting Started:</span></span>

<span data-ttu-id="85f0c-558">Пользователю не нужно нажимать какие-либо кнопки в пользовательском интерфейсе, чтобы применить эту возможность.</span><span class="sxs-lookup"><span data-stu-id="85f0c-558">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="85f0c-559">Она включена по умолчанию для DOCM-файлов в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="85f0c-559">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="85f0c-560">Чтобы применить ее, пользователю нужно сохранить DOCM-файл в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="85f0c-560">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-561">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-561">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-562">Создайте DOCM-файл в OneDrive для бизнеса, поделитесь им с коллегами и работайте совместно!</span><span class="sxs-lookup"><span data-stu-id="85f0c-562">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-563">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-563">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-564">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-564">Word</span></span> 
- <span data-ttu-id="85f0c-565">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="85f0c-565">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="85f0c-566">Решена проблема со сбоем, происходившим при ответе на примечания</span><span class="sxs-lookup"><span data-stu-id="85f0c-566">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="85f0c-567">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="85f0c-567">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-568">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-568">Excel</span></span>
- <span data-ttu-id="85f0c-569">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="85f0c-569">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-570">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-570">PowerPoint</span></span>
- <span data-ttu-id="85f0c-571">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-571">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-572">Outlook</span></span>
- <span data-ttu-id="85f0c-573">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="85f0c-573">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="85f0c-574">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="85f0c-574">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="85f0c-575">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="85f0c-575">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-576">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-576">Access</span></span>
- <span data-ttu-id="85f0c-577">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="85f0c-577">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="85f0c-578">Исправлена проблема, из-за которой пользователи не могли присвоить свойству DisplayControl для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="85f0c-578">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-579">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-579">Project</span></span>
- <span data-ttu-id="85f0c-580">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-580">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="85f0c-581">1 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-581">March 1, 2019</span></span> 
<span data-ttu-id="85f0c-582">Версия 1903 (сборка 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="85f0c-582">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-583">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="85f0c-583">What's New</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-584">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-584">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="85f0c-585">Синхронизированные цвета для отслеживания изменений, примечаний и совместной работы в режиме реального времени</span><span class="sxs-lookup"><span data-stu-id="85f0c-585">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="85f0c-586">Исправления в наших продуктах теперь обеспечивают отображение одинаковым цветом примечаний, изменений и указателя мыши при совместной работе.</span><span class="sxs-lookup"><span data-stu-id="85f0c-586">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-587">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-587">Getting Started:</span></span>

<span data-ttu-id="85f0c-588">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="85f0c-588">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="85f0c-589">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="85f0c-589">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-590">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-590">Scenarios to Try:</span></span>

<span data-ttu-id="85f0c-591">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="85f0c-591">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="85f0c-592">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="85f0c-592">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-593">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-593">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-594">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-594">Word</span></span> 
- <span data-ttu-id="85f0c-595">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="85f0c-595">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="85f0c-596">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="85f0c-596">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-597">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-597">Excel</span></span>
- <span data-ttu-id="85f0c-598">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="85f0c-598">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-599">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-599">PowerPoint</span></span>
- <span data-ttu-id="85f0c-600">Исправлена проблема с размером изображения слайда при использовании @упоминаний в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-600">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-601">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-601">Outlook</span></span>
- <span data-ttu-id="85f0c-602">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="85f0c-602">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="85f0c-603">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="85f0c-603">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="85f0c-604">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="85f0c-604">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-605">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-605">Access</span></span>
- <span data-ttu-id="85f0c-606">Обновлен текст запроса, отображаемый для подтверждения обновления связей таблицы с источником данных</span><span class="sxs-lookup"><span data-stu-id="85f0c-606">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="85f0c-607">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="85f0c-607">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="85f0c-608">Исправлена проблема, из-за которой пользователи не могли присвоить свойству "Тип элемента управления" для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="85f0c-608">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-609">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-609">Project</span></span>
- <span data-ttu-id="85f0c-610">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-610">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="85f0c-611">15 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-611">February 15, 2019</span></span> 
<span data-ttu-id="85f0c-612">Версия 1903 (сборка 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="85f0c-612">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="85f0c-613">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="85f0c-613">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-614">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-614">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="85f0c-615">Улучшения перехода "Трансформация" — трансформация по имени</span><span class="sxs-lookup"><span data-stu-id="85f0c-615">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="85f0c-616">Укажите фигуры, которые нужно трансформировать</span><span class="sxs-lookup"><span data-stu-id="85f0c-616">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-617">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-617">Getting Started:</span></span>

- <span data-ttu-id="85f0c-618">Чтобы при переходе "Трансформация" два объекта обрабатывались как одинаковые, пользователь может переименовать фигуры с помощью области выделения.</span><span class="sxs-lookup"><span data-stu-id="85f0c-618">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="85f0c-619">Имя должно начинаться с двух восклицательных знаков</span><span class="sxs-lookup"><span data-stu-id="85f0c-619">The name must be prefaced with “!!”</span></span> <span data-ttu-id="85f0c-620">("!!"), чтобы использовать его при трансформации для переопределения стандартного сопоставления, например "!!Имя".</span><span class="sxs-lookup"><span data-stu-id="85f0c-620">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="85f0c-621">Пользователи могут продолжать переименовывать фигуры, используя любые имена, которые не начинаются с "!!",</span><span class="sxs-lookup"><span data-stu-id="85f0c-621">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="85f0c-622">не беспокоясь о том, что это изменит работу перехода "Трансформация".</span><span class="sxs-lookup"><span data-stu-id="85f0c-622">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-623">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-623">Scenarios to Try:</span></span>

- <span data-ttu-id="85f0c-624">Вставьте фигуру на слайд, например прямоугольник</span><span class="sxs-lookup"><span data-stu-id="85f0c-624">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="85f0c-625">Создайте новый слайд</span><span class="sxs-lookup"><span data-stu-id="85f0c-625">Create a new slide</span></span>
- <span data-ttu-id="85f0c-626">Вставьте другую фигуру на втором слайде, например треугольник</span><span class="sxs-lookup"><span data-stu-id="85f0c-626">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="85f0c-627">Откройте область выделения и присвойте имя "!!фигура" прямоугольнику на слайде 1 и треугольнику на слайде 2.</span><span class="sxs-lookup"><span data-stu-id="85f0c-627">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="85f0c-628">Примените переход "Трансформация" ко второму слайду</span><span class="sxs-lookup"><span data-stu-id="85f0c-628">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="85f0c-629">Улучшения перехода "Трансформация" — графические элементы SmartArt</span><span class="sxs-lookup"><span data-stu-id="85f0c-629">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="85f0c-630">Трансформация графических элементов SmartArt с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="85f0c-630">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-631">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-631">Getting Started:</span></span>

<span data-ttu-id="85f0c-632">Аналогичное использование перехода "Трансформация" при применении графических элементов SmartArt</span><span class="sxs-lookup"><span data-stu-id="85f0c-632">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-633">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-633">Scenarios to Try:</span></span>

- <span data-ttu-id="85f0c-634">Вставьте графический элемент SmartArt на слайд</span><span class="sxs-lookup"><span data-stu-id="85f0c-634">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="85f0c-635">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="85f0c-635">Duplicate the Slide</span></span>
- <span data-ttu-id="85f0c-636">Поменяйте размер, измените или переместите графический элемент SmartArt на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="85f0c-636">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="85f0c-637">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="85f0c-637">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="85f0c-638">Улучшения перехода "Трансформация" — таблицы</span><span class="sxs-lookup"><span data-stu-id="85f0c-638">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="85f0c-639">Трансформация таблиц с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="85f0c-639">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="85f0c-640">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="85f0c-640">Getting Started:</span></span>
<span data-ttu-id="85f0c-641">Аналогичное использование перехода "Трансформация" при применении таблиц</span><span class="sxs-lookup"><span data-stu-id="85f0c-641">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-642">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-642">Scenarios to Try:</span></span>

- <span data-ttu-id="85f0c-643">Вставьте таблицу на слайд</span><span class="sxs-lookup"><span data-stu-id="85f0c-643">Insert a Table in a slide</span></span>
- <span data-ttu-id="85f0c-644">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="85f0c-644">Duplicate the slide</span></span>
- <span data-ttu-id="85f0c-645">Поменяйте размер, измените или переместите таблицу на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="85f0c-645">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="85f0c-646">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="85f0c-646">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="85f0c-647">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher и Visio</span><span class="sxs-lookup"><span data-stu-id="85f0c-647">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="85f0c-648">Легкое переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="85f0c-648">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="85f0c-649">Новый диспетчер учетных записей отображает все рабочие и личные учетные записи в одном месте и позволяет управлять переключением между ними.</span><span class="sxs-lookup"><span data-stu-id="85f0c-649">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="85f0c-650">Этот обновленный интерфейс уточняет способ выполненного входа и обеспечивает возможность переключения между рабочими и личными учетными записями без выхода из системы или появления сложных диалоговых окон.</span><span class="sxs-lookup"><span data-stu-id="85f0c-650">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="85f0c-652">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="85f0c-652">Scenarios to Try:</span></span>
- <span data-ttu-id="85f0c-653">Переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="85f0c-653">Switch between accounts</span></span>
- <span data-ttu-id="85f0c-654">Добавление новой учетной записи [Примечание. Рекомендуется сначала открыть "Файл" | "Учетная запись" | "Подключенные службы" и удалить все личные службы, подключенные к рабочей учетной записи и наоборот]</span><span class="sxs-lookup"><span data-stu-id="85f0c-654">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="85f0c-655">Выход из учетной записи</span><span class="sxs-lookup"><span data-stu-id="85f0c-655">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="85f0c-656">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-656">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-657">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-657">Word</span></span> 
- <span data-ttu-id="85f0c-658">Исправлена проблема с предварительным просмотром контекста для таблиц и изображений</span><span class="sxs-lookup"><span data-stu-id="85f0c-658">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-659">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-659">Excel</span></span>
- <span data-ttu-id="85f0c-660">Исправлена ошибка, из-за которой при использовании темы "Черная" текст в поле поиска автофильтра был белого цвета</span><span class="sxs-lookup"><span data-stu-id="85f0c-660">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="85f0c-661">Исправлена проблема с согласованным пользовательским интерфейсом для новой надстройки Office</span><span class="sxs-lookup"><span data-stu-id="85f0c-661">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-662">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-662">PowerPoint</span></span>
- <span data-ttu-id="85f0c-663">Исправлена проблема с автоматическим расширением области отображения во время презентации на ноутбуках и планшетах.</span><span class="sxs-lookup"><span data-stu-id="85f0c-663">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-664">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-664">Outlook</span></span>
- <span data-ttu-id="85f0c-665">Исправлена проблема с отображением кнопки "Отправить в OneNote"</span><span class="sxs-lookup"><span data-stu-id="85f0c-665">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-666">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-666">Access</span></span>
- <span data-ttu-id="85f0c-667">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-667">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-668">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-668">Project</span></span>
- <span data-ttu-id="85f0c-669">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-669">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="85f0c-670">11 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-670">February 11, 2019</span></span>
<span data-ttu-id="85f0c-671">Версия 1903 (сборка 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="85f0c-671">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="85f0c-672">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-672">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-673">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-673">Word</span></span> 
- <span data-ttu-id="85f0c-674">Исправлена ошибка, из-за которой некоторые настроенные стили нельзя было применить в Word Online</span><span class="sxs-lookup"><span data-stu-id="85f0c-674">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="85f0c-675">Исправлены проблемы предварительного просмотра контекста, связанные с форматированными объектами в Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-675">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="85f0c-676">Исправлена ошибка, из-за которой при вставке списков происходил сбой Word.</span><span class="sxs-lookup"><span data-stu-id="85f0c-676">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-677">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-677">Excel</span></span>
- <span data-ttu-id="85f0c-678">Исправлена ошибка, из-за которой добавляемые пробелы после числовых форматов не отображались при отсутствии обозначения денежной единицы</span><span class="sxs-lookup"><span data-stu-id="85f0c-678">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="85f0c-679">Исправлена проблема с автоматическим определением акций</span><span class="sxs-lookup"><span data-stu-id="85f0c-679">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-680">PowerPoint</span></span>
- <span data-ttu-id="85f0c-681">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-681">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-682">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-682">Outlook</span></span>
- <span data-ttu-id="85f0c-683">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-683">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-684">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-684">Access</span></span>
- <span data-ttu-id="85f0c-685">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-685">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-686">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-686">Project</span></span>
- <span data-ttu-id="85f0c-687">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-687">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="85f0c-688">1 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="85f0c-688">February 1, 2019</span></span> 
<span data-ttu-id="85f0c-689">Версия 1902 (сборка 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="85f0c-689">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="85f0c-690">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="85f0c-690">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="85f0c-691">Word</span><span class="sxs-lookup"><span data-stu-id="85f0c-691">Word</span></span> 
- <span data-ttu-id="85f0c-692">Устранена проблема с изменением размера ячеек во внедренной таблице Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-692">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="85f0c-693">Устранена проблема с копированием и вставкой фигур на полотне</span><span class="sxs-lookup"><span data-stu-id="85f0c-693">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="85f0c-694">Excel</span><span class="sxs-lookup"><span data-stu-id="85f0c-694">Excel</span></span>
- <span data-ttu-id="85f0c-695">Исправлена ошибка с открытием файлов из Excel Web App</span><span class="sxs-lookup"><span data-stu-id="85f0c-695">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="85f0c-696">Исправлена ошибка, вызывавшая сбой при сохранении CSV-файла в формате XLSX из-за длины имени файла</span><span class="sxs-lookup"><span data-stu-id="85f0c-696">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="85f0c-697">Исправлено контекстное меню для отображения параметров контекстного меню</span><span class="sxs-lookup"><span data-stu-id="85f0c-697">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="85f0c-698">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="85f0c-698">PowerPoint</span></span>
- <span data-ttu-id="85f0c-699">Устранена проблема, из-за которой пользователи не могли использовать сочетания клавиш CTRL+ALT+7 и CTRL+ALT+8 для ввода квадратных скобок</span><span class="sxs-lookup"><span data-stu-id="85f0c-699">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="85f0c-700">Исправлена ошибка, из-за которой при вставке локального видео в файл PPT уменьшалось место на диске "C"</span><span class="sxs-lookup"><span data-stu-id="85f0c-700">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="85f0c-701">Исправлена кнопка "Публикация в Microsoft Stream", не отображавшаяся у некоторых пользователей</span><span class="sxs-lookup"><span data-stu-id="85f0c-701">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="85f0c-702">Outlook</span><span class="sxs-lookup"><span data-stu-id="85f0c-702">Outlook</span></span>
- <span data-ttu-id="85f0c-703">Исправлена ошибка, из-за которой в представлении задач в календаре неправильно отображалась тема задачи.</span><span class="sxs-lookup"><span data-stu-id="85f0c-703">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="85f0c-704">Access</span><span class="sxs-lookup"><span data-stu-id="85f0c-704">Access</span></span>
- <span data-ttu-id="85f0c-705">Исправлена проблема с масштабированием диаграмм</span><span class="sxs-lookup"><span data-stu-id="85f0c-705">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="85f0c-706">Project</span><span class="sxs-lookup"><span data-stu-id="85f0c-706">Project</span></span>
- <span data-ttu-id="85f0c-707">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="85f0c-707">Various performance and stability fixes</span></span>
