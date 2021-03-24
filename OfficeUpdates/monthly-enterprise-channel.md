---
title: Заметки о выпусках Monthly Enterprise Channel в 2020 г.
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Monthly Enterprise Channel для Приложений Microsoft 365 в 2020 г. для ИТ-специалистов.
ms.openlocfilehash: 34bbcb4700033ba2668b9766d053362424dcf356
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169728"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a><span data-ttu-id="c80ef-103">Заметки о выпусках Monthly Enterprise Channel в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="c80ef-103">Release notes for Monthly Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="c80ef-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Monthly Enterprise Channel в 2020 г. для Приложений Microsoft 365 для предприятий, Приложений Microsoft 365 для бизнеса, а также классических приложений Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="c80ef-104">These release notes provide information about new features and non-security updates that are included in Monthly Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="c80ef-105">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="c80ef-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="c80ef-106">Дополнительные сведения см. в [этой статье](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="c80ef-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

[//]: # (НЕ УДАЛЯТЬ)



## <a name="version-2101-march-09"></a><span data-ttu-id="c80ef-108">Версия 2101: 9 марта</span><span class="sxs-lookup"><span data-stu-id="c80ef-108">Version 2101: March 09</span></span>
<span data-ttu-id="c80ef-109">*Версия 2101 (сборка 13628.20528)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-109">*Version 2101 (Build 13628.20528)*</span></span>

<span data-ttu-id="c80ef-110">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-110">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-112">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-112">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-113">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-113">Excel</span></span>

- <span data-ttu-id="c80ef-114">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="c80ef-114">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="c80ef-115">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-115">Outlook</span></span>

- <span data-ttu-id="c80ef-116">Исправлена проблема, из-за которой значок шифрования не отображался в сообщениях, отправленных с использованием параметра "Только с шифрованием".</span><span class="sxs-lookup"><span data-stu-id="c80ef-116">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="c80ef-117">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал соответствующий флажок.</span><span class="sxs-lookup"><span data-stu-id="c80ef-117">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="c80ef-118">Исправлена проблема, из-за которой возникали проблемы с отображением правильной подписи по умолчанию в веб-клиенте Outlook.</span><span class="sxs-lookup"><span data-stu-id="c80ef-118">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="c80ef-119">Исправлена проблема, приводившая к зависанию у пользователей облачных параметров при обновлении настроек.</span><span class="sxs-lookup"><span data-stu-id="c80ef-119">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="c80ef-120">Исправлена проблема, из-за которой приложение иногда неожиданно закрывалось, если пользователи выполняли поиск в Outlook.</span><span class="sxs-lookup"><span data-stu-id="c80ef-120">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="c80ef-121">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="c80ef-121">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="c80ef-122">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось в определенных сценариях поиска.</span><span class="sxs-lookup"><span data-stu-id="c80ef-122">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-123">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-123">Project</span></span>

- <span data-ttu-id="c80ef-124">Устранена проблема, из-за которой сведение базовых затрат выполнялось неправильно, если затратный ресурс был назначен задаче-вехе.</span><span class="sxs-lookup"><span data-stu-id="c80ef-124">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


- <span data-ttu-id="c80ef-125">Исправлена проблема, из-за которой границы не отображались для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-125">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="c80ef-126">Исправлена проблема, из-за которой не работало перетаскивание для задач в представлении визуального оптимизатора ресурсов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-126">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c80ef-127">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-127">Office Suite</span></span>

- <span data-ttu-id="c80ef-128">Устранена проблема, связанная с уведомлениями о событиях контроллера мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="c80ef-128">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="c80ef-129">Устранена проблема, связанная с расчетом времени в обработчике проигрывателя мультимедиа.</span><span class="sxs-lookup"><span data-stu-id="c80ef-129">Fixes an issue related to media player engine timing.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2012-march-09"></a><span data-ttu-id="c80ef-131">Версия 2012: 9 марта</span><span class="sxs-lookup"><span data-stu-id="c80ef-131">Version 2012: March 09</span></span>
<span data-ttu-id="c80ef-132">*Версия 2012 (сборка 13530.20628)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-132">*Version 2012 (Build 13530.20628)*</span></span>

<span data-ttu-id="c80ef-133">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-133">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2012-february-09"></a><span data-ttu-id="c80ef-134">Версия 2012: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="c80ef-134">Version 2012: February 09</span></span>
<span data-ttu-id="c80ef-135">*Версия 2012 (сборка 13530.20528)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-135">*Version 2012 (Build 13530.20528)*</span></span>

<span data-ttu-id="c80ef-136">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-136">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-138">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-138">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-139">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-139">Excel</span></span>

- <span data-ttu-id="c80ef-140">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-140">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="c80ef-141">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-141">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="c80ef-142">**Ведение журнала аудита действий с метками конфиденциальности.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, эти сведения теперь становятся доступными администраторам в журналах аудита Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c80ef-142">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="c80ef-143">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="c80ef-143">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="c80ef-144">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-144">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="c80ef-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-145">Outlook</span></span>

- <span data-ttu-id="c80ef-146">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-146">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="c80ef-147">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-147">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="c80ef-148">**Перерыв между собраниями.** Дайте участникам время передохнуть или перейти в другое место, задав время начала собрания на 5–10 минут позже по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="c80ef-148">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="c80ef-149">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-149">Learn more</span></span>](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- <span data-ttu-id="c80ef-150">**Ведение журнала аудита действий с метками конфиденциальности.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, эти сведения теперь становятся доступными администраторам в журналах аудита Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c80ef-150">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="c80ef-151">**Каждое собрание — собрание по сети.** Измените параметры календаря, чтобы все создаваемые собрания были собраниями Teams по умолчанию. Благодаря этому вам больше не нужно помнить о нажатии кнопки "Собрание Teams".</span><span class="sxs-lookup"><span data-stu-id="c80ef-151">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="c80ef-152">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="c80ef-152">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="c80ef-153">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-153">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

- <span data-ttu-id="c80ef-154">**Каждое собрание — собрание по сети.** Измените параметры календаря, чтобы все создаваемые собрания были собраниями Teams по умолчанию. Благодаря этому вам больше не нужно помнить о нажатии кнопки "Собрание Teams".</span><span class="sxs-lookup"><span data-stu-id="c80ef-154">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="c80ef-155">**Новая функция "Поиск помещений".** Поиск конференц-залов с учетом различных возможностей. </span><span class="sxs-lookup"><span data-stu-id="c80ef-155">**New room finder:** Search for conference rooms by different capabilities.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c80ef-156">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-156">PowerPoint</span></span>

- <span data-ttu-id="c80ef-157">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-157">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="c80ef-158">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-158">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="c80ef-159">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="c80ef-159">See details in [blog post](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="c80ef-160">**Ведение журнала аудита действий с метками конфиденциальности.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, эти сведения теперь становятся доступными администраторам в журналах аудита Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c80ef-160">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="c80ef-161">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="c80ef-161">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="c80ef-162">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-162">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a><span data-ttu-id="c80ef-163">Visio</span><span class="sxs-lookup"><span data-stu-id="c80ef-163">Visio</span></span>

- <span data-ttu-id="c80ef-164">**Новые наборы элементов и фигуры Azure.** Мы добавили множество дополнительных наборов элементов, чтобы помочь вам создавать современные диаграммы Azure.</span><span class="sxs-lookup"><span data-stu-id="c80ef-164">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="c80ef-165">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-165">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="c80ef-166">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-166">Word</span></span>

- <span data-ttu-id="c80ef-167">**Поддержка буфера обмена SVG:** теперь SVG-содержимое можно вставлять из Office в сторонние приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-167">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="c80ef-168">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-168">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="c80ef-169">**Ведение журнала аудита действий с метками конфиденциальности.** Когда пользователи присваивают, изменяют или удаляют метки конфиденциальности из своих документов и писем, эти сведения теперь становятся доступными администраторам в журналах аудита Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c80ef-169">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="c80ef-170">**Правительственные учреждения. Используйте метки конфиденциальности для документов и сообщений электронной почты.** Функции присвоения меток конфиденциальности теперь доступны пользователям в средах GCC и GCC H.</span><span class="sxs-lookup"><span data-stu-id="c80ef-170">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="c80ef-171">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-171">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-174">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-174">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-175">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-175">Excel</span></span>

- <span data-ttu-id="c80ef-176">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="c80ef-176">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="c80ef-177">Исправлена проблема, из-за которой для некоторых пользователей неверно отображалась панель сообщений, уведомляющая о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="c80ef-177">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="c80ef-178">Исправлена ​​проблема, из-за которой Excel мог оставлять макросы отключенными без запроса при открытии файла надстройки Excel, содержащего макросы Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="c80ef-178">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="c80ef-179">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck).</span><span class="sxs-lookup"><span data-stu-id="c80ef-179">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="c80ef-180">Исправлена проблема, из-за которой Excel мог неожиданно закрываться при использовании меню "Дополнительные вычисления" для сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="c80ef-180">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="c80ef-181">Исправлена проблема, нарушавшая работу некоторых устаревших макросов Excel 4.0 и Excel 5.0, а также некоторых вызовов VBA в dialogsheets.show.</span><span class="sxs-lookup"><span data-stu-id="c80ef-181">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


### <a name="outlook"></a><span data-ttu-id="c80ef-182">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-182">Outlook</span></span>

- <span data-ttu-id="c80ef-183">Исправлена проблема, из-за которой не удавалось сохранить измененную подпись после предложения пользователю этого действия.</span><span class="sxs-lookup"><span data-stu-id="c80ef-183">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="c80ef-184">Исправлена проблема, из-за которой у некоторых пользователей приложение Outlook неожиданно закрывалось при выполнении определенных сценариев поиска.</span><span class="sxs-lookup"><span data-stu-id="c80ef-184">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="c80ef-185">Исправлена проблема, приводившая к зависаниям у некоторых пользователей при загрузке их календарей.</span><span class="sxs-lookup"><span data-stu-id="c80ef-185">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="c80ef-186">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="c80ef-186">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-187">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-187">PowerPoint</span></span>

- <span data-ttu-id="c80ef-188">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="c80ef-188">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="c80ef-189">Это изменение устраняет проблему с отображением шрифтов в формулах.</span><span class="sxs-lookup"><span data-stu-id="c80ef-189">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="c80ef-190">Это изменение устраняет проблему с заливками путей при объединении фигур определенных геометрий.</span><span class="sxs-lookup"><span data-stu-id="c80ef-190">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c80ef-191">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-191">Office Suite</span></span>

- <span data-ttu-id="c80ef-192">Anaheim WebView пока не поддерживает службу Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="c80ef-192">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="c80ef-193">С этим исправлением платформа надстроек Office откатывается на веб-представление уровнем ниже в среде с поддержкой WIP.</span><span class="sxs-lookup"><span data-stu-id="c80ef-193">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="c80ef-194">Это может быть Edge Spartan WebView или Trident WebView в зависимости от среды на компьютере пользователя.</span><span class="sxs-lookup"><span data-stu-id="c80ef-194">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="c80ef-195">Оба веб-представления уровнем ниже поддерживают WIP.</span><span class="sxs-lookup"><span data-stu-id="c80ef-195">Both down level WebViews support WIP.</span></span>


- <span data-ttu-id="c80ef-196">Оптимизированный размер двоичного файла.</span><span class="sxs-lookup"><span data-stu-id="c80ef-196">Optimized binary size.</span></span>


- <span data-ttu-id="c80ef-197">Исправлена последовательность закрытия файлов. Теперь все независимые компоненты закрываются правильно.</span><span class="sxs-lookup"><span data-stu-id="c80ef-197">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2011-february-09"></a><span data-ttu-id="c80ef-199">Версия 2011: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="c80ef-199">Version 2011: February 09</span></span>
<span data-ttu-id="c80ef-200">*Версия 2011 (сборка 13426.20658)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-200">*Version 2011 (Build 13426.20658)*</span></span>

<span data-ttu-id="c80ef-201">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-201">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2011-january-12"></a><span data-ttu-id="c80ef-202">Версия 2011: 12 января</span><span class="sxs-lookup"><span data-stu-id="c80ef-202">Version 2011: January 12</span></span>
<span data-ttu-id="c80ef-203">*Версия 2011 (сборка 13426.20526)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-203">*Version 2011 (Build 13426.20526)*</span></span>

<span data-ttu-id="c80ef-204">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-204">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-206">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-206">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-207">Access</span><span class="sxs-lookup"><span data-stu-id="c80ef-207">Access</span></span>

- <span data-ttu-id="c80ef-208">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-208">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-209">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-209">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-210">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-210">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="c80ef-211">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-211">Excel</span></span>

- <span data-ttu-id="c80ef-212">**Создание переменных для использования в формулах.** Повышайте производительность, удобочитаемость и компонуемость с помощью функции ПУСТЬ.</span><span class="sxs-lookup"><span data-stu-id="c80ef-212">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="c80ef-213">Эта функция позволяет создавать именованные переменные в новых или уже существующих формулах.</span><span class="sxs-lookup"><span data-stu-id="c80ef-213">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="c80ef-214">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-214">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="c80ef-215">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-215">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="c80ef-216">**Создание настраиваемого типа данных в Power Query.** Используйте любой источник данных для создания настраиваемого типа данных, позволяющего загружать несколько связанных элементов информации в один столбец.</span><span class="sxs-lookup"><span data-stu-id="c80ef-216">**Create a custom data type in Power Query:** Use any data source to create a custom data type that lets you load multiple related pieces of information into one column.</span></span> [<span data-ttu-id="c80ef-217">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-217">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="c80ef-218">Дополнительные сведения см. в этой [публикации в блоге](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span><span class="sxs-lookup"><span data-stu-id="c80ef-218">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="c80ef-219">**Присвоение новому листу имени после исходного запроса.** При загрузке данных на новый лист ему будет присваиваться имя исходного запроса.</span><span class="sxs-lookup"><span data-stu-id="c80ef-219">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="c80ef-220">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-220">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-221">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-221">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-222">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-222">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="c80ef-223">OneNote</span><span class="sxs-lookup"><span data-stu-id="c80ef-223">OneNote</span></span>

- <span data-ttu-id="c80ef-224">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-224">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-225">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-225">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-226">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-226">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="c80ef-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-227">Outlook</span></span>

- <span data-ttu-id="c80ef-228">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-228">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-229">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-229">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-230">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-230">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a><span data-ttu-id="c80ef-231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-231">PowerPoint</span></span>

- <span data-ttu-id="c80ef-232">**Библиотека видео.** Улучшайте свои документы с помощью библиотеки специально отобранных бесплатных видеоматериалов, доступных в приложении.</span><span class="sxs-lookup"><span data-stu-id="c80ef-232">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app.</span></span>

- <span data-ttu-id="c80ef-233">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-233">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-234">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-234">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-235">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-235">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="c80ef-236">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-236">Project</span></span>

- <span data-ttu-id="c80ef-237">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-237">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-238">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-238">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-239">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-239">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="c80ef-240">Publisher</span><span class="sxs-lookup"><span data-stu-id="c80ef-240">Publisher</span></span>

- <span data-ttu-id="c80ef-241">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-241">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-242">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-242">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-243">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-243">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="c80ef-244">Visio</span><span class="sxs-lookup"><span data-stu-id="c80ef-244">Visio</span></span>

- <span data-ttu-id="c80ef-245">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-245">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-246">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-246">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-247">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-247">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="c80ef-248">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-248">Word</span></span>

- <span data-ttu-id="c80ef-249">**Автоматическое переключение на темы Office**. Office может автоматически переключать темы в соответствии с параметрами темы Windows 10.</span><span class="sxs-lookup"><span data-stu-id="c80ef-249">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="c80ef-250">Перейдите в меню "Файл" > "Учетная запись" и выберите "Использовать системные настройки" в раскрывающемся списке тем Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-250">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="c80ef-251">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-251">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-254">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-254">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-255">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-255">Excel</span></span>

- <span data-ttu-id="c80ef-256">Исправлена проблема, из-за которой Excel неверно отображал панель сообщений, уведомлявшую о доступности новой версии файла, и заставлял пользователя сохранить его изменения в копии книги или отменить их.</span><span class="sxs-lookup"><span data-stu-id="c80ef-256">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="c80ef-257">Исправлена ​​проблема, из-за которой Excel мог оставлять макросы отключенными без запроса при открытии файла надстройки Excel, содержащего макросы Excel 4.0.</span><span class="sxs-lookup"><span data-stu-id="c80ef-257">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="outlook"></a><span data-ttu-id="c80ef-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-258">Outlook</span></span>

- <span data-ttu-id="c80ef-259">Исправлена проблема, из-за которой некоторые пользователи не видели подписей в раскрывающемся списке подписей, хотя у них настроена одна или несколько подписей.</span><span class="sxs-lookup"><span data-stu-id="c80ef-259">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="c80ef-260">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="c80ef-260">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="c80ef-261">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="c80ef-261">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="c80ef-262">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="c80ef-262">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="c80ef-263">0 = параметры filetime исключены.</span><span class="sxs-lookup"><span data-stu-id="c80ef-263">0 = filetimes are excluded.</span></span> <span data-ttu-id="c80ef-264">1 = (по умолчанию) параметры filetime включены.</span><span class="sxs-lookup"><span data-stu-id="c80ef-264">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="c80ef-265">Исправлена проблема, приводившая к исчезновению встроенных изображений при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="c80ef-265">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="c80ef-266">Исправлена ошибка, из-за которой происходил сбой события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="c80ef-266">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="c80ef-267">Исправлена проблема, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="c80ef-267">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="c80ef-268">Исправлена проблема, из-за которой исходные участники некоторых собраний получали уведомление об отмене, когда другой участник перенаправлял приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="c80ef-268">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-269">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-269">PowerPoint</span></span>

- <span data-ttu-id="c80ef-270">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="c80ef-270">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="c80ef-271">Исправлена проблема, приводившая к ошибке при сохранении файла после дублирования слайда, содержащего недавно записанный звук.</span><span class="sxs-lookup"><span data-stu-id="c80ef-271">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="c80ef-272">Исправлена проблема VBA, приводившая к сбою Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="c80ef-272">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="c80ef-273">Это изменение устраняет проблему с обработкой ошибок, которые могут возникнуть во время загрузки видео.</span><span class="sxs-lookup"><span data-stu-id="c80ef-273">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="c80ef-274">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-274">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-275">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-275">Project</span></span>

- <span data-ttu-id="c80ef-276">Исправлена проблема, из-за которой могли открываться определенные проекты, если имелась проблема с файлом проекта в определенной части загрузки.</span><span class="sxs-lookup"><span data-stu-id="c80ef-276">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="c80ef-277">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-277">Word</span></span>

- <span data-ttu-id="c80ef-278">Исправление ошибки утверждения, вызываемой оптимизированными шлюзами, затрагивающими Word.</span><span class="sxs-lookup"><span data-stu-id="c80ef-278">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


- <span data-ttu-id="c80ef-279">Исправлена ошибка, в результате которой стили документов заменялись другими стилями из шаблона.</span><span class="sxs-lookup"><span data-stu-id="c80ef-279">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="c80ef-280">Это изменение исправляет проблему, связанную с курсором при редактировании документа.</span><span class="sxs-lookup"><span data-stu-id="c80ef-280">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="c80ef-281">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-281">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c80ef-282">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-282">Office Suite</span></span>

- <span data-ttu-id="c80ef-283">Исправлена проблема, из-за которой установка более новой версии Office поверх некоторых старых версий могла приводить к ухудшению функциональности (например, невозможности использовать Power Query) из-за отсутствия записей в реестре.</span><span class="sxs-lookup"><span data-stu-id="c80ef-283">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="c80ef-284">Исправлена ​​проблема, из-за которой файл открывался со статусом НЕ SyncBacked, если URL-адрес из кэша и URL-адрес из OneDrive НЕ совпадали.</span><span class="sxs-lookup"><span data-stu-id="c80ef-284">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="c80ef-285">Исправлена проблема, из-за которой параметр SaveRequestManagerCam приводил к закрытию приложения, а не возвращал ошибку.</span><span class="sxs-lookup"><span data-stu-id="c80ef-285">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-january-12"></a><span data-ttu-id="c80ef-287">Версия 2010: 12 января</span><span class="sxs-lookup"><span data-stu-id="c80ef-287">Version 2010: January 12</span></span>
<span data-ttu-id="c80ef-288">*Версия 2010 (сборка 13328.20550)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-288">*Version 2010 (Build 13328.20550)*</span></span>

<span data-ttu-id="c80ef-289">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-289">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2010-december-08"></a><span data-ttu-id="c80ef-290">Версия 2010: 08 декабря</span><span class="sxs-lookup"><span data-stu-id="c80ef-290">Version 2010: December 08</span></span>
<span data-ttu-id="c80ef-291">*Версия 2010 (сборка 13328.20478)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-291">*Version 2010 (Build 13328.20478)*</span></span>

<span data-ttu-id="c80ef-292">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-292">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-294">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-294">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-295">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-295">Excel</span></span>

- <span data-ttu-id="c80ef-296">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 / Microsoft 365 и планом обслуживания Power BI Pro.</span><span class="sxs-lookup"><span data-stu-id="c80ef-296">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="c80ef-297">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-297">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="c80ef-298">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="c80ef-298">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="c80ef-299">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-299">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="c80ef-300">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-300">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="c80ef-301">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-301">Outlook</span></span>

- <span data-ttu-id="c80ef-302">**Обновления для задач пользовательского интерфейса:** визуальное обновление элементов задач</span><span class="sxs-lookup"><span data-stu-id="c80ef-302">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="c80ef-303">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="c80ef-303">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="c80ef-304">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="c80ef-304">You can change permissions so all recipients have access.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c80ef-305">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-305">PowerPoint</span></span>

- <span data-ttu-id="c80ef-306">**Экспорт GIF с анимацией в диапазоне:** можно выбрать диапазон слайдов при экспорте в GIF с анимацией</span><span class="sxs-lookup"><span data-stu-id="c80ef-306">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="c80ef-307">**Создание GIF с прозрачным фоном:** при экспорте в GIF с анимацией новый параметр позволит сделать фон прозрачным.</span><span class="sxs-lookup"><span data-stu-id="c80ef-307">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="c80ef-308">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)</span><span class="sxs-lookup"><span data-stu-id="c80ef-308">See details in [blog post](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-311">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-311">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-312">Доступ</span><span class="sxs-lookup"><span data-stu-id="c80ef-312">Access</span></span>

- <span data-ttu-id="c80ef-313">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-313">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="c80ef-314">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-314">Outlook</span></span>

- <span data-ttu-id="c80ef-315">Исправлена проблема, из-за которой в Outlook создавалась вторая пустая подпись для пользователей, включивших облачные параметры.</span><span class="sxs-lookup"><span data-stu-id="c80ef-315">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="c80ef-316">Исправлена проблема, из-за которой облачные параметры не включались по умолчанию для пользователей.</span><span class="sxs-lookup"><span data-stu-id="c80ef-316">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="c80ef-317">Исправлена проблема, из-за которой не сохранялись изменения, внесенные в подпись пользователя.</span><span class="sxs-lookup"><span data-stu-id="c80ef-317">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="c80ef-318">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="c80ef-318">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="c80ef-319">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="c80ef-319">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="c80ef-320">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="c80ef-320">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="c80ef-321">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="c80ef-321">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="c80ef-322">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="c80ef-322">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="c80ef-323">0 = параметры filetime исключены.</span><span class="sxs-lookup"><span data-stu-id="c80ef-323">0 = filetimes are excluded.</span></span>  <span data-ttu-id="c80ef-324">1 = (по умолчанию) параметры filetime включены.</span><span class="sxs-lookup"><span data-stu-id="c80ef-324">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="c80ef-325">Исправлена проблема, приводившая к сбою события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="c80ef-325">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="c80ef-326">Исправлена проблема, из-за которой исходные участники некоторых собраний получали уведомление об отмене, когда другой участник перенаправлял приглашение на собрание.</span><span class="sxs-lookup"><span data-stu-id="c80ef-326">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="c80ef-327">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="c80ef-327">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-328">PowerPoint</span></span>

- <span data-ttu-id="c80ef-329">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="c80ef-329">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="c80ef-330">Исправление для устранения проблемы с использованием IRM/защищенных документов при возникновении ошибки слияния.</span><span class="sxs-lookup"><span data-stu-id="c80ef-330">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="c80ef-331">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-331">Fixed an issue with copy/paste of an equation from Word to Powerpoint.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-332">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-332">Project</span></span>

- <span data-ttu-id="c80ef-333">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="c80ef-333">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="c80ef-334">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="c80ef-334">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="c80ef-335">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChange имело неправильное значение в случае изменения задержки в представлении типа "Форма задачи".</span><span class="sxs-lookup"><span data-stu-id="c80ef-335">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="visio"></a><span data-ttu-id="c80ef-336">Visio</span><span class="sxs-lookup"><span data-stu-id="c80ef-336">Visio</span></span>

- <span data-ttu-id="c80ef-337">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-337">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="c80ef-338">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-338">Word</span></span>

- <span data-ttu-id="c80ef-339">Исправлена ошибка, связанная с копированием и вставкой уравнения из Word в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-339">Fixed an issue with copy/paste of an equation from Word to Powerpoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c80ef-340">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-340">Office Suite</span></span>

- <span data-ttu-id="c80ef-341">Исправлена проблема, из-за которой защита от потери данных в конечной точке Microsoft 365 не могла классифицировать документы Office на диске.</span><span class="sxs-lookup"><span data-stu-id="c80ef-341">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="c80ef-342">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение "Мало тонера" или "Нет тонера", несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="c80ef-342">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c80ef-343">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="c80ef-343">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="c80ef-344">Устранена проблема, из-за которой возникала ошибка при копировании и вставке текста из комментария в Excel.</span><span class="sxs-lookup"><span data-stu-id="c80ef-344">Fixed an issue where an error would occur when copy/paste text from a comment into Excel.</span></span>


- <span data-ttu-id="c80ef-345">Исправлена проблема, из-за которой попытка выполнить действие "Сохранить как" завершалась неудачей в определенных сценариях.</span><span class="sxs-lookup"><span data-stu-id="c80ef-345">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="c80ef-346">Исправлена проблема, вызывавшая сбой при попытке сохранить файлы, перешедшие из состояния "синхронизировано" в состояние "только для сервера".</span><span class="sxs-lookup"><span data-stu-id="c80ef-346">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-december-08"></a><span data-ttu-id="c80ef-348">Версия 2009: 08 декабря</span><span class="sxs-lookup"><span data-stu-id="c80ef-348">Version 2009: December 08</span></span>
<span data-ttu-id="c80ef-349">*Версия 2009 (сборка 13231.20620)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-349">*Version 2009 (Build 13231.20620)*</span></span>

<span data-ttu-id="c80ef-350">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2009-november-10"></a><span data-ttu-id="c80ef-351">Версия 2009: 10 ноября</span><span class="sxs-lookup"><span data-stu-id="c80ef-351">Version 2009: November 10</span></span>
<span data-ttu-id="c80ef-352">*Версия 2009 (сборка 13231.20514)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-352">*Version 2009 (Build 13231.20514)*</span></span>

<span data-ttu-id="c80ef-353">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-353">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-355">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-355">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-356">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-356">Excel</span></span>

- <span data-ttu-id="c80ef-357">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="c80ef-357">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c80ef-358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-358">PowerPoint</span></span>

- <span data-ttu-id="c80ef-359">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="c80ef-359">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-360">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-360">Word</span></span>

- <span data-ttu-id="c80ef-361">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="c80ef-361">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-364">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-364">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c80ef-365">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-365">Outlook</span></span>

- <span data-ttu-id="c80ef-366">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="c80ef-366">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="c80ef-367">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="c80ef-367">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="c80ef-368">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="c80ef-368">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="c80ef-369">Исправлена проблема, из-за которой у некоторых пользователей Outlook неожиданно запускался в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="c80ef-369">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="c80ef-370">Исправлена проблема, из-за которой при поиске в некэшированных общих календарях не возвращались никакие результаты.</span><span class="sxs-lookup"><span data-stu-id="c80ef-370">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="c80ef-371">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="c80ef-371">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="c80ef-372">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="c80ef-372">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-373">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-373">PowerPoint</span></span>

- <span data-ttu-id="c80ef-374">Исправлена проблема, из-за которой замедлялось совместное редактирование файлов, содержащих большие количества определенного типа объекта данных (E2o).</span><span class="sxs-lookup"><span data-stu-id="c80ef-374">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="c80ef-375">Исправлена проблема с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="c80ef-375">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="c80ef-376">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-376">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-377">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-377">Project</span></span>

- <span data-ttu-id="c80ef-378">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="c80ef-378">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="c80ef-379">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="c80ef-379">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="c80ef-380">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="c80ef-380">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


### <a name="word"></a><span data-ttu-id="c80ef-381">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-381">Word</span></span>

- <span data-ttu-id="c80ef-382">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="c80ef-382">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c80ef-383">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-383">Office Suite</span></span>

- <span data-ttu-id="c80ef-384">Исправлена проблема, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="c80ef-384">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="c80ef-385">Исправлена проблема, из-за которой защита от потери данных в конечной точке Microsoft 365 не могла классифицировать документы Office на диске.</span><span class="sxs-lookup"><span data-stu-id="c80ef-385">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="c80ef-386">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение "Мало тонера" или "Нет тонера", несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="c80ef-386">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c80ef-387">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="c80ef-387">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-november-10"></a><span data-ttu-id="c80ef-389">Версия 2008: 10 ноября</span><span class="sxs-lookup"><span data-stu-id="c80ef-389">Version 2008: November 10</span></span>
<span data-ttu-id="c80ef-390">*Версия 2008 (сборка 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-390">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="c80ef-391">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-391">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-393">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-393">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-394">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-394">Excel</span></span>

- <span data-ttu-id="c80ef-395">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="c80ef-395">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="c80ef-396">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="c80ef-396">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="c80ef-397">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="c80ef-397">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="c80ef-398">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="c80ef-398">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="c80ef-399">Исправлена проблема, из-за которой некоторые функции выдавали неправильный результат после загрузки книги.</span><span class="sxs-lookup"><span data-stu-id="c80ef-399">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="c80ef-400">Исправлена проблема с неожиданным завершением работы приложения, что было связано со ссылками и именованными диапазонами надстройки XLAM.</span><span class="sxs-lookup"><span data-stu-id="c80ef-400">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>

### <a name="outlook"></a><span data-ttu-id="c80ef-401">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-401">Outlook</span></span>

- <span data-ttu-id="c80ef-402">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке искажались при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="c80ef-402">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="c80ef-403">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="c80ef-403">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="c80ef-404">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="c80ef-404">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="c80ef-405">Исправлена проблема, из-за которой поисковые запросы в календарях групп не возвращали никаких результатов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-405">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="c80ef-406">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="c80ef-406">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="c80ef-407">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-407">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="c80ef-408">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="c80ef-408">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="c80ef-409">Исправлена проблема, из-за которой необязательные сетевые функции блокировали загрузку веб-надстроек.</span><span class="sxs-lookup"><span data-stu-id="c80ef-409">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span><br /><span data-ttu-id="c80ef-410">Дополнительные сведения см. в этой [публикации в блоге](https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-410">See details in [blog post](https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-411">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-411">PowerPoint</span></span>

- <span data-ttu-id="c80ef-412">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="c80ef-412">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="c80ef-413">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-413">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c80ef-414">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-414">Office Suite</span></span>

- <span data-ttu-id="c80ef-415">Исправлена проблема для коммерческих пользователей, применяющих System Center Configuration Manager или другие средства управления для обновления Office с использованием защиты от потери данных в конечной точке Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c80ef-415">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="c80ef-416">Исправлена проблема с неработающим API сообщений для надстроек Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-416">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-october-13"></a><span data-ttu-id="c80ef-418">Версия 2008: 13 октября</span><span class="sxs-lookup"><span data-stu-id="c80ef-418">Version 2008: October 13</span></span>
<span data-ttu-id="c80ef-419">*Версия 2008 (сборка 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-419">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="c80ef-420">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-420">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-422">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-422">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-423">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-423">Excel</span></span>

- <span data-ttu-id="c80ef-424">**Есть вопросы? Спросите у Excel.** Функция "Идеи" в Excel дает возможность задавать вопросы о данных. Нет необходимости тратить время на составление формул (доступно только на английском языке).</span><span class="sxs-lookup"><span data-stu-id="c80ef-424">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="c80ef-425">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-425">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="c80ef-426">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-426">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="c80ef-427">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="c80ef-427">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="c80ef-428">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="c80ef-428">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="c80ef-429">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-429">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="c80ef-430">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-430">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="c80ef-431">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-431">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="c80ef-432">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="c80ef-432">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="c80ef-433">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-433">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="c80ef-434">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="c80ef-434">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="c80ef-435">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-435">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="c80ef-436">**Создание полированных диаграмм Visio в Excel:** создайте блок-схему или организационную диаграмму, поместив данные на лист.</span><span class="sxs-lookup"><span data-stu-id="c80ef-436">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="c80ef-437">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-437">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="c80ef-438">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-438">Outlook</span></span>

- <span data-ttu-id="c80ef-439">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="c80ef-439">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="c80ef-440">**Новая карточка профиля в Outlook.** Новая карточка профиля в Outlook включает улучшенное представление организации и соответствует стилю карточек Outlook Web.</span><span class="sxs-lookup"><span data-stu-id="c80ef-440">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span> [<span data-ttu-id="c80ef-441">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-441">Learn more</span></span>](https://support.office.com/article/e80f931f-5fc4-4a59-ba6e-c1e35a85b501)

### <a name="powerpoint"></a><span data-ttu-id="c80ef-442">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-442">PowerPoint</span></span>

- <span data-ttu-id="c80ef-443">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-443">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="c80ef-444">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="c80ef-444">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="c80ef-445">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="c80ef-445">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="c80ef-446">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-446">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="c80ef-447">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-447">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="c80ef-448">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-448">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-449">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-449">Word</span></span>

- <span data-ttu-id="c80ef-450">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="c80ef-450">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="c80ef-451">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="c80ef-451">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="c80ef-452">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="c80ef-452">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="c80ef-453">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-453">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="c80ef-454">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-454">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="c80ef-455">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-455">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-458">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-458">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-459">Доступ</span><span class="sxs-lookup"><span data-stu-id="c80ef-459">Access</span></span>

- <span data-ttu-id="c80ef-460">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="c80ef-460">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


- <span data-ttu-id="c80ef-461">Это изменение исправляет проблему, из-за которой Access мог аварийно завершать работу при запуске функции масштаба (SHIFT+F2) для редактирования текста.</span><span class="sxs-lookup"><span data-stu-id="c80ef-461">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="c80ef-462">Эта проблема уже устранена и больше не должна вызывать сбой.</span><span class="sxs-lookup"><span data-stu-id="c80ef-462">This issue has now been resolved and you should no longer experience a crash.</span></span>


### <a name="excel"></a><span data-ttu-id="c80ef-463">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-463">Excel</span></span>

- <span data-ttu-id="c80ef-464">Исправлена проблема, которая могла вызывать предупреждение о поврежденной книге, если она содержала формулы с ЕСНД().</span><span class="sxs-lookup"><span data-stu-id="c80ef-464">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="c80ef-465">Исправлена проблема, из-за которой Excel мог аварийно завершать работу при использовании экспресс-анализа после закрепления верхней строки листа.</span><span class="sxs-lookup"><span data-stu-id="c80ef-465">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="c80ef-466">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="c80ef-466">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="c80ef-467">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="c80ef-467">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="c80ef-468">Исправлена ошибка с API PivotDateFilter, из-за которой условия фильтрации "До" и "После" менялись местами.</span><span class="sxs-lookup"><span data-stu-id="c80ef-468">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


### <a name="outlook"></a><span data-ttu-id="c80ef-469">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-469">Outlook</span></span>

- <span data-ttu-id="c80ef-470">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="c80ef-470">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="c80ef-471">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="c80ef-471">Do you want to download them anyway?</span></span> <span data-ttu-id="c80ef-472">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="c80ef-472">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="c80ef-473">Устранена проблема, из-за которой контекстное меню не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="c80ef-473">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="c80ef-474">Исправлена проблема, из-за которой возникали аномалии при использовании компактного представления.</span><span class="sxs-lookup"><span data-stu-id="c80ef-474">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="c80ef-475">Устранена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="c80ef-475">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>


- <span data-ttu-id="c80ef-476">Устранена проблема, из-за которой страница помощника по планированию не отображалась для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="c80ef-476">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="c80ef-477">Исправлена проблема с производительностью при отправке вложений.</span><span class="sxs-lookup"><span data-stu-id="c80ef-477">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="c80ef-478">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="c80ef-478">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="c80ef-479">Исправлена проблема, из-за которой при открытии облачного вложения ошибка отображалась на странице безопасных ссылок, а не в открываемом документе.</span><span class="sxs-lookup"><span data-stu-id="c80ef-479">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="c80ef-480">Исправлена проблема, из-за которой возникали периодические сбои при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="c80ef-480">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="c80ef-481">Исправлена проблема, из-за которой пользователи не могли закрыть общие календари, щелкнув значок "X" в углу.</span><span class="sxs-lookup"><span data-stu-id="c80ef-481">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="c80ef-482">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="c80ef-482">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="c80ef-483">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="c80ef-483">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="c80ef-484">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="c80ef-484">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="c80ef-485">Исправлена проблема, из-за которой иногда не удавалось применить параметр "Включить улучшения общего календаря" к существующим общим календарям.</span><span class="sxs-lookup"><span data-stu-id="c80ef-485">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="c80ef-486">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="c80ef-486">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-487">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-487">PowerPoint</span></span>

- <span data-ttu-id="c80ef-488">Исправлена проблема, которая приводила к сбою в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-488">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


- <span data-ttu-id="c80ef-489">Исправление системы безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="c80ef-489">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="c80ef-490">Это изменение исправляет проблему, связанную с функцией экспорта в GIF с анимацией, когда не выполнялся экспорт при нажатии кнопки "Экспорт".</span><span class="sxs-lookup"><span data-stu-id="c80ef-490">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-491">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-491">Project</span></span>

- <span data-ttu-id="c80ef-492">Исправлена проблема, из-за которой дата окончания проекта не обновляется для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-492">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="c80ef-493">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="c80ef-493">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="c80ef-494">Skype</span><span class="sxs-lookup"><span data-stu-id="c80ef-494">Skype</span></span>

- <span data-ttu-id="c80ef-495">Цвет кожи танцующего смайлика изменен на нейтральный.</span><span class="sxs-lookup"><span data-stu-id="c80ef-495">Changed dancing emoticon skin tone to neutral color.</span></span>


### <a name="visio"></a><span data-ttu-id="c80ef-496">Visio</span><span class="sxs-lookup"><span data-stu-id="c80ef-496">Visio</span></span>

- <span data-ttu-id="c80ef-497">Пользователи сообщают о сбоях динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="c80ef-497">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="c80ef-498">Самый распространенный сбой в вилке за июль.</span><span class="sxs-lookup"><span data-stu-id="c80ef-498">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="c80ef-499">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-499">Word</span></span>

- <span data-ttu-id="c80ef-500">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec</span><span class="sxs-lookup"><span data-stu-id="c80ef-500">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


- <span data-ttu-id="c80ef-501">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="c80ef-501">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="c80ef-502">Устранена проблема, которая могла вызвать сбой при загрузке Word.</span><span class="sxs-lookup"><span data-stu-id="c80ef-502">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="c80ef-503">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="c80ef-503">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="c80ef-504">Исправлена проблема, из-за которой мог возникать сбой при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="c80ef-504">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="c80ef-505">Устранена проблема, из-за которой пользователь мог потерять контент при изменении размера фигуры.</span><span class="sxs-lookup"><span data-stu-id="c80ef-505">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="c80ef-506">Исправлена проблема, которая вызывала сбой при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="c80ef-506">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="c80ef-507">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-507">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>


- <span data-ttu-id="c80ef-508">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="c80ef-508">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c80ef-509">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-509">Office Suite</span></span>

- <span data-ttu-id="c80ef-510">Это изменение устраняет сбой при запуске приложений Office из-за невозможности загрузки d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="c80ef-510">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="c80ef-511">Исправлена высокая загрузка ЦП при простое с использованием GIF или анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="c80ef-511">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="c80ef-512">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="c80ef-512">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c80ef-513">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="c80ef-513">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-october-13"></a><span data-ttu-id="c80ef-515">Версия 2007: 13 октября</span><span class="sxs-lookup"><span data-stu-id="c80ef-515">Version 2007: October 13</span></span>
<span data-ttu-id="c80ef-516">*Версия 2007 (сборка 13029.20708)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-516">*Version 2007 (Build 13029.20708)*</span></span>

<span data-ttu-id="c80ef-517">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-517">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-519">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-520">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-520">Excel</span></span>

- <span data-ttu-id="c80ef-521">Исправлена ошибка с API PivotDateFilter, из-за которой условия фильтрации "До" и "После" менялись местами.</span><span class="sxs-lookup"><span data-stu-id="c80ef-521">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-september-08"></a><span data-ttu-id="c80ef-523">Версия 2007: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="c80ef-523">Version 2007: September 08</span></span>
<span data-ttu-id="c80ef-524">*Версия 2007 (сборка 13029.20534)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-524">*Version 2007 (Build 13029.20534)*</span></span>

<span data-ttu-id="c80ef-525">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-525">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-527">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-527">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c80ef-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-528">Outlook</span></span>

- <span data-ttu-id="c80ef-529">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="c80ef-529">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="c80ef-530">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-530">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="c80ef-531">**Быстрое повторное открытие элементов из предыдущего сеанса.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="c80ef-531">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="c80ef-532">После нормального или аварийного завершения работы Outlook при повторном открытии приложения можно быстро перезапустить его элементы.</span><span class="sxs-lookup"><span data-stu-id="c80ef-532">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="c80ef-533">По умолчанию эта функция включена.</span><span class="sxs-lookup"><span data-stu-id="c80ef-533">This feature is on by default.</span></span> <span data-ttu-id="c80ef-534">Чтобы ее отключить, выберите "Параметры > Общие > Параметры запуска".</span><span class="sxs-lookup"><span data-stu-id="c80ef-534">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-535">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-535">Word</span></span>

- <span data-ttu-id="c80ef-536">**Сохранение текста в векторах.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Excel, Word и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-536">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c80ef-537">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-537">Office Suite</span></span>

- <span data-ttu-id="c80ef-538">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-538">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="c80ef-539">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="c80ef-539">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="c80ef-540">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-540">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-543">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-543">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-544">Доступ</span><span class="sxs-lookup"><span data-stu-id="c80ef-544">Access</span></span>

- <span data-ttu-id="c80ef-545">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="c80ef-545">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


### <a name="excel"></a><span data-ttu-id="c80ef-546">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-546">Excel</span></span>

- <span data-ttu-id="c80ef-547">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы могла возникать ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="c80ef-547">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


- <span data-ttu-id="c80ef-548">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="c80ef-548">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="c80ef-549">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-549">Outlook</span></span>

- <span data-ttu-id="c80ef-550">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="c80ef-550">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="c80ef-551">Устранена проблема, из-за которой у пользователей Outlook возникали проблемы с навигацией в компактных представлениях.</span><span class="sxs-lookup"><span data-stu-id="c80ef-551">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="c80ef-552">Устранена проблема, которая иногда приводила к аварийному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="c80ef-552">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


- <span data-ttu-id="c80ef-553">Устранена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="c80ef-553">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="c80ef-554">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="c80ef-554">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="c80ef-555">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="c80ef-555">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="c80ef-556">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="c80ef-556">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="c80ef-557">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-557">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="c80ef-558">Устранена проблема, из-за которой пользователи CLP могут столкнуться со сбоем при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="c80ef-558">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="c80ef-559">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-559">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-560">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-560">PowerPoint</span></span>

- <span data-ttu-id="c80ef-561">Устранена проблема со сбоем в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-561">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-562">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-562">Project</span></span>

- <span data-ttu-id="c80ef-563">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-563">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="c80ef-564">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости были скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="c80ef-564">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="c80ef-565">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="c80ef-565">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="c80ef-566">Исправлена проблема, из-за которой проект в нерабочем состоянии нельзя было открыть.</span><span class="sxs-lookup"><span data-stu-id="c80ef-566">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



### <a name="office-suite"></a><span data-ttu-id="c80ef-567">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-567">Office Suite</span></span>

- <span data-ttu-id="c80ef-568">Исправлена проблема, из-за которой пользователи видели элементы или содержимое пользовательского интерфейса, которое не отображается при определенных условиях. В частности, при входе или выходе из режима докладчика и использовании нескольких мониторов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-568">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="c80ef-569">Исправлена проблема, из-за которой сообщение о процессе выполнения появлялось, даже если переход на полную версию продукта завершен.</span><span class="sxs-lookup"><span data-stu-id="c80ef-569">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="c80ef-570">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="c80ef-570">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="c80ef-571">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="c80ef-571">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="c80ef-572">Старая область общего доступа, не основанная на веб-службе, при закрытии документа могла вызывать сбой, если область общего доступа была открыта.</span><span class="sxs-lookup"><span data-stu-id="c80ef-572">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="c80ef-573">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="c80ef-573">This is now fixed.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-september-08"></a><span data-ttu-id="c80ef-575">Версия 2006: 08 сентября</span><span class="sxs-lookup"><span data-stu-id="c80ef-575">Version 2006: September 08</span></span>
<span data-ttu-id="c80ef-576">*Версия 2006 (сборка 13001.20648)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-576">*Version 2006 (Build 13001.20648)*</span></span>

<span data-ttu-id="c80ef-577">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-577">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2006-august-11"></a><span data-ttu-id="c80ef-578">Версия 2006: 11 августа</span><span class="sxs-lookup"><span data-stu-id="c80ef-578">Version 2006: August 11</span></span>
<span data-ttu-id="c80ef-579">*Версия 2006 (сборка 13001.20520)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-579">*Version 2006 (Build 13001.20520)*</span></span>

<span data-ttu-id="c80ef-580">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-580">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-582">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-582">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-583">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-583">Excel</span></span>

- <span data-ttu-id="c80ef-584">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="c80ef-584">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="c80ef-585">**Фильтруйте и сортируйте, не мешая другим:** Теперь вы можете сортировать и фильтровать файлы Excel во время совместной работы с другими пользователями в представлении листа.</span><span class="sxs-lookup"><span data-stu-id="c80ef-585">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="c80ef-586">Благодаря этой новой функции вам не будет мешать выполняемая другими пользователями сортировка и фильтрация при совместной работе с документом.</span><span class="sxs-lookup"><span data-stu-id="c80ef-586">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="c80ef-587">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-587">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a><span data-ttu-id="c80ef-588">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-588">Outlook</span></span>

- <span data-ttu-id="c80ef-589">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="c80ef-589">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="c80ef-590">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="c80ef-590">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="c80ef-591">**Новая опция, позволяющая отключить предложения @ упоминания при составлении писем в Outlook:** Считаете ли вы средство @ упоминания более раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="c80ef-591">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="c80ef-592">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="c80ef-592">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="c80ef-593">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-593">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="c80ef-594">**Сохраняйте высокое качество фотографий при отправке их в электронном письме.** Доступен новый параметр Outlook для ограничения сжатия изображений при их отправке в составе содержимого письма.</span><span class="sxs-lookup"><span data-stu-id="c80ef-594">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c80ef-595">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-595">PowerPoint</span></span>

- <span data-ttu-id="c80ef-596">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="c80ef-596">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="c80ef-597">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="c80ef-597">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="c80ef-598">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="c80ef-598">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-599">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-599">Word</span></span>

- <span data-ttu-id="c80ef-600">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="c80ef-600">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="c80ef-601">**Выразите мысль другими словами.** Если вы хотите выразить мысль по-другому, можно воспользоваться функцией переписывания.</span><span class="sxs-lookup"><span data-stu-id="c80ef-601">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="c80ef-602">Она предлагает другие варианты, подходящие для ваших фраз.</span><span class="sxs-lookup"><span data-stu-id="c80ef-602">Rewrite offers alternatives for finessing your phrases.</span></span><br /><span data-ttu-id="c80ef-603">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-603">See details in [blog post](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-606">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-606">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-607">Доступ</span><span class="sxs-lookup"><span data-stu-id="c80ef-607">Access</span></span>

- <span data-ttu-id="c80ef-608">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="c80ef-608">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="c80ef-609">Устранена проблема со вставкой связанных таблиц SQL, содержащих поле удостоверения (например, счетчик).</span><span class="sxs-lookup"><span data-stu-id="c80ef-609">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


### <a name="excel"></a><span data-ttu-id="c80ef-610">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-610">Excel</span></span>

- <span data-ttu-id="c80ef-611">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="c80ef-611">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="c80ef-612">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы могла возникать ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="c80ef-612">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="c80ef-613">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="c80ef-613">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="c80ef-614">Для рабочих книг, доступных только для чтения, могла действовать автоматическая классификация документов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-614">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

### <a name="onenote"></a><span data-ttu-id="c80ef-615">OneNote</span><span class="sxs-lookup"><span data-stu-id="c80ef-615">OneNote</span></span>

- <span data-ttu-id="c80ef-616">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-616">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="c80ef-617">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-617">Outlook</span></span>

- <span data-ttu-id="c80ef-618">Мы устранили проблемы при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-618">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="c80ef-619">Исправлена проблема, из-за которой поиск возможности предложения функции не возвращал результатов и не позволял пользователям поделиться идеями.</span><span class="sxs-lookup"><span data-stu-id="c80ef-619">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="c80ef-620">Исправлена проблема, из-за которой не выполнялось действие при нажатии CTRL и щелчка мыши при включенных параметрах облака.</span><span class="sxs-lookup"><span data-stu-id="c80ef-620">Addresses an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

- <span data-ttu-id="c80ef-621">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="c80ef-621">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="c80ef-622">Исправлена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="c80ef-622">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="c80ef-623">Исправлена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="c80ef-623">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="c80ef-624">Исправлена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="c80ef-624">Addresses an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

### <a name="project"></a><span data-ttu-id="c80ef-625">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-625">Project</span></span>

- <span data-ttu-id="c80ef-626">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="c80ef-626">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="c80ef-627">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="c80ef-627">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="c80ef-628">Исправлена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="c80ef-628">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-629">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-629">Word</span></span>

- <span data-ttu-id="c80ef-630">Мы устранили проблемы при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-630">We fixed an issue for copy and paste SVG image.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c80ef-631">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-631">Office Suite</span></span>

- <span data-ttu-id="c80ef-632">Мы отправили часть AppV51 на доработку, чтобы исправить в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="c80ef-632">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="c80ef-633">При закрытии файлов Office мог произойти сбой из-за проблем с синхронизацией.</span><span class="sxs-lookup"><span data-stu-id="c80ef-633">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="c80ef-634">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="c80ef-634">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-august-11"></a><span data-ttu-id="c80ef-636">Версия 2005: 11 августа</span><span class="sxs-lookup"><span data-stu-id="c80ef-636">Version 2005: August 11</span></span>
<span data-ttu-id="c80ef-637">*Версия 2005 (сборка 12827.20656)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-637">*Version 2005 (Build 12827.20656)*</span></span>

<span data-ttu-id="c80ef-638">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-638">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2005-july-14"></a><span data-ttu-id="c80ef-639">Версия 2005: 14 июля</span><span class="sxs-lookup"><span data-stu-id="c80ef-639">Version 2005: July 14</span></span>
<span data-ttu-id="c80ef-640">*Версия 2005 (сборка 12827.20538)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-640">*Version 2005 (Build 12827.20538)*</span></span>

<span data-ttu-id="c80ef-641">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-641">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-643">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-643">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="c80ef-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-644">Outlook</span></span>

- <span data-ttu-id="c80ef-645">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="c80ef-645">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="c80ef-646">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-646">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-649">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-649">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-650">Доступ</span><span class="sxs-lookup"><span data-stu-id="c80ef-650">Access</span></span>

- <span data-ttu-id="c80ef-651">Исправлена проблема, препятствующая возможности вызова расширенного типа данных "Дата/время" без сбоев приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-651">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="c80ef-652">Проблема исправлена, поэтому теперь вы можете вернуться к последней версии Access и использовать DAO/VBA для управления и изменения типа данных Decimal.</span><span class="sxs-lookup"><span data-stu-id="c80ef-652">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

### <a name="excel"></a><span data-ttu-id="c80ef-653">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-653">Excel</span></span>

- <span data-ttu-id="c80ef-654">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="c80ef-654">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c80ef-655">В некоторых случаях при щелчке гиперссылки внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="c80ef-655">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="c80ef-656">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="c80ef-656">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="c80ef-657">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="c80ef-657">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="c80ef-658">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-658">Outlook</span></span>

- <span data-ttu-id="c80ef-659">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="c80ef-659">Addresses an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="c80ef-660">Исправлена проблема, из-за которой поиск возможности предложения функции не возвращал результатов и не позволял пользователям поделиться идеями.</span><span class="sxs-lookup"><span data-stu-id="c80ef-660">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="c80ef-661">Исправлена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="c80ef-661">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="c80ef-662">Исправлена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="c80ef-662">Addresses an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="c80ef-663">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="c80ef-663">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="c80ef-664">Исправлена проблема, которая приводила в некоторых ситуациях к периодическим зависаниям и сбоям.</span><span class="sxs-lookup"><span data-stu-id="c80ef-664">Addresses an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="c80ef-665">Исправлена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="c80ef-665">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="c80ef-666">Устранена проблема, из-за которой при обновлении этих правил в Outlook появлялось сообщение "Правила на этом компьютере противоречат правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="c80ef-666">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="c80ef-667">Исправлена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="c80ef-667">Addresses an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="c80ef-668">Устранена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="c80ef-668">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="c80ef-669">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="c80ef-669">Addresses an issue with the clp auditing event for the reply/forward label.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c80ef-670">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-670">PowerPoint</span></span>

- <span data-ttu-id="c80ef-671">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="c80ef-671">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="c80ef-672">Исправлена проблема со сбоем панели предложений.</span><span class="sxs-lookup"><span data-stu-id="c80ef-672">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-673">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-673">Project</span></span>

- <span data-ttu-id="c80ef-674">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="c80ef-674">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="c80ef-675">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="c80ef-675">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="skype"></a><span data-ttu-id="c80ef-676">Skype</span><span class="sxs-lookup"><span data-stu-id="c80ef-676">Skype</span></span>

- <span data-ttu-id="c80ef-677">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="c80ef-677">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="c80ef-678">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-678">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="c80ef-679">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="c80ef-679">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-680">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-680">Word</span></span>

- <span data-ttu-id="c80ef-681">Устранена проблема, которая могла вызвать сбой при перетаскивании части содержимого из приложения.</span><span class="sxs-lookup"><span data-stu-id="c80ef-681">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c80ef-682">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-682">Office Suite</span></span>

- <span data-ttu-id="c80ef-683">Это изменение устраняет потенциальные зависания при загрузке и воспроизведении анимированных данных, таких как GIF или трехмерные модели.</span><span class="sxs-lookup"><span data-stu-id="c80ef-683">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="c80ef-684">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="c80ef-684">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="c80ef-685">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="c80ef-685">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="c80ef-686">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="c80ef-686">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="c80ef-687">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="c80ef-687">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="c80ef-688">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="c80ef-688">This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-july-14"></a><span data-ttu-id="c80ef-690">Версия 2004: 14 июля</span><span class="sxs-lookup"><span data-stu-id="c80ef-690">Version 2004: July 14</span></span>
<span data-ttu-id="c80ef-691">*Версия 2004 (сборка 12730.20602)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-691">*Version 2004 (Build 12730.20602)*</span></span>

<span data-ttu-id="c80ef-692">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-692">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2004-june-09"></a><span data-ttu-id="c80ef-693">Версия 2004: 09 июня</span><span class="sxs-lookup"><span data-stu-id="c80ef-693">Version 2004: June 09</span></span>
<span data-ttu-id="c80ef-694">*Версия 2004 (сборка 12730.20430)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-694">*Version 2004 (Build 12730.20430)*</span></span>

<span data-ttu-id="c80ef-695">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-695">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-697">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-697">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-698">Доступ</span><span class="sxs-lookup"><span data-stu-id="c80ef-698">Access</span></span>

- <span data-ttu-id="c80ef-699">**Быстрое добавление таблиц.** Используйте область задач "Добавление таблиц", которая остается открытой во время работы, чтобы добавлять таблицы в связи и запросы.</span><span class="sxs-lookup"><span data-stu-id="c80ef-699">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="c80ef-700">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-700">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="c80ef-701">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-701">Excel</span></span>

- <span data-ttu-id="c80ef-702">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="c80ef-702">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="c80ef-703">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-703">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="c80ef-704">**Поддержка соединителя Facebook заканчивается:** Начиная с апреля 2020 года Excel больше не будет поддерживать подключения к внешним данным, которые используют соединитель Facebook.</span><span class="sxs-lookup"><span data-stu-id="c80ef-704">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="c80ef-705">**Новые изображения, чтобы оживить книги.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в книгах.</span><span class="sxs-lookup"><span data-stu-id="c80ef-705">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="c80ef-706">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="c80ef-706">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c80ef-707">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-707">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="c80ef-708">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-708">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="outlook"></a><span data-ttu-id="c80ef-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-709">Outlook</span></span>

- <span data-ttu-id="c80ef-710">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="c80ef-710">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="c80ef-711">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-711">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="c80ef-712">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="c80ef-712">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="c80ef-713">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="c80ef-713">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="c80ef-714">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-714">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="c80ef-715">**Обновления Календаря.** Ознакомьтесь с наглядными обновлениями, упрощающими сканирование календаря.</span><span class="sxs-lookup"><span data-stu-id="c80ef-715">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="c80ef-716">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-716">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="c80ef-717">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-717">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="c80ef-718">**Новые изображения, чтобы оживить сообщения.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="c80ef-718">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="c80ef-719">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="c80ef-719">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c80ef-720">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-720">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="c80ef-721">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-721">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c80ef-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-722">PowerPoint</span></span>

- <span data-ttu-id="c80ef-723">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="c80ef-723">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="c80ef-724">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-724">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="c80ef-725">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="c80ef-725">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="c80ef-726">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-726">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="c80ef-727">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-727">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="c80ef-728">**Новые изображения, чтобы оживить слайды.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в презентациях.</span><span class="sxs-lookup"><span data-stu-id="c80ef-728">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="c80ef-729">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="c80ef-729">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c80ef-730">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-730">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="c80ef-731">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-731">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-732">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-732">Word</span></span>

- <span data-ttu-id="c80ef-733">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="c80ef-733">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="c80ef-734">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="c80ef-734">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="c80ef-735">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-735">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="c80ef-736">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="c80ef-736">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="c80ef-737">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-737">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="c80ef-738">**Новые изображения, чтобы оживить документы.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в документах.</span><span class="sxs-lookup"><span data-stu-id="c80ef-738">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="c80ef-739">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="c80ef-739">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="c80ef-740">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-740">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="c80ef-741">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-741">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="c80ef-742">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-742">Office Suite</span></span>

- <span data-ttu-id="c80ef-743">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="c80ef-743">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-746">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-746">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c80ef-747">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-747">Excel</span></span>

- <span data-ttu-id="c80ef-748">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="c80ef-748">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="c80ef-749">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="c80ef-749">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="c80ef-750">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="c80ef-750">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="c80ef-751">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="c80ef-751">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

### <a name="outlook"></a><span data-ttu-id="c80ef-752">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-752">Outlook</span></span>

- <span data-ttu-id="c80ef-753">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="c80ef-753">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="c80ef-754">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="c80ef-754">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="c80ef-755">Устранена проблема, из-за которой у пользователей возникали сбои при отображении всплывающих уведомлений.</span><span class="sxs-lookup"><span data-stu-id="c80ef-755">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>

- <span data-ttu-id="c80ef-756">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="c80ef-756">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="c80ef-757">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="c80ef-757">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="c80ef-758">Устранена проблема, приводившая к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="c80ef-758">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

### <a name="project"></a><span data-ttu-id="c80ef-759">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-759">Project</span></span>

- <span data-ttu-id="c80ef-760">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="c80ef-760">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="c80ef-761">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="c80ef-761">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c80ef-762">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-762">Office Suite</span></span>

- <span data-ttu-id="c80ef-763">Исправлена проблема технологии "Нажми и работай", из-за которой происходил сбой обновления при попытке жесткой связи символьных ссылок.</span><span class="sxs-lookup"><span data-stu-id="c80ef-763">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="c80ef-764">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="c80ef-764">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="c80ef-765">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="c80ef-765">This change would fix this issue.</span></span>

- <span data-ttu-id="c80ef-766">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="c80ef-766">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="c80ef-767">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="c80ef-767">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="c80ef-768">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="c80ef-768">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-june-09"></a><span data-ttu-id="c80ef-770">Версия 2003: 09 июня</span><span class="sxs-lookup"><span data-stu-id="c80ef-770">Version 2003: June 09</span></span>
<span data-ttu-id="c80ef-771">*Версия 2003 (сборка 12624.20708)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-771">*Version 2003 (Build 12624.20708)*</span></span>

<span data-ttu-id="c80ef-772">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-772">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-774">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-774">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c80ef-775">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-775">Office Suite</span></span>

- <span data-ttu-id="c80ef-776">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="c80ef-776">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-may-12"></a><span data-ttu-id="c80ef-778">Версия 2003: 12 мая</span><span class="sxs-lookup"><span data-stu-id="c80ef-778">Version 2003: May 12</span></span>
<span data-ttu-id="c80ef-779">*Версия 2003 (сборка 12624.20588)*</span><span class="sxs-lookup"><span data-stu-id="c80ef-779">*Version 2003 (Build 12624.20588)*</span></span>

<span data-ttu-id="c80ef-780">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="c80ef-780">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="c80ef-782">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="c80ef-782">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c80ef-783">Access</span><span class="sxs-lookup"><span data-stu-id="c80ef-783">Access</span></span>

- <span data-ttu-id="c80ef-784">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="c80ef-784">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="c80ef-785">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="c80ef-785">Search and replace text in SQL View.</span></span> <span data-ttu-id="c80ef-786">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="c80ef-786">Select multiple tables in the Relationships window.</span></span>

### <a name="excel"></a><span data-ttu-id="c80ef-787">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-787">Excel</span></span>

- <span data-ttu-id="c80ef-788">**Ввод формулы, возвращающей несколько значений.** Теперь вы можете быстро ввести формулу, возвращающую несколько значений, которые автоматически переносятся в смежные ячейки.</span><span class="sxs-lookup"><span data-stu-id="c80ef-788">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="c80ef-789">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-789">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="c80ef-790">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-790">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="c80ef-791">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="c80ef-791">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="c80ef-792">**Шесть эффективных функций.** Добавлено шесть новых функций для улучшения электронных таблиц: ФИЛЬТР, СОРТ, СОРТПО, УНИК, ПОСЛЕДОВ и СЛУЧМАССИВ.</span><span class="sxs-lookup"><span data-stu-id="c80ef-792">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="c80ef-793">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-793">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="c80ef-794">**Посмотрите налево, посмотрите направо… ПРОСМОТРX уже доступен!:** построчно просмотрите и найдите нужные элементы в таблице или диапазоне с помощью функции ПРОМОТРX.</span><span class="sxs-lookup"><span data-stu-id="c80ef-794">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="c80ef-795">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-795">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="c80ef-796">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-796">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="c80ef-797">**Читайте и отвечайте на ходу.** Отвечайте на комментарии и упоминания непосредственно в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="c80ef-797">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="c80ef-798">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-798">Outlook</span></span>

- <span data-ttu-id="c80ef-799">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="c80ef-799">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="c80ef-800">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-800">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="c80ef-801">**Политика именования групп.** Политика именования групп позволяет ИТ-администратору стандартизировать имена групп, созданных пользователями в организации, а также управлять ими.</span><span class="sxs-lookup"><span data-stu-id="c80ef-801">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="c80ef-802">Администратор может требовать добавления специального префикса и суффикса к имени группы при ее создании и может запретить использование определенных слов.</span><span class="sxs-lookup"><span data-stu-id="c80ef-802">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="c80ef-803">Это позволяет уменьшить использование недопустимых слов в названиях групп, а также управлять отображением групп в каталоге.</span><span class="sxs-lookup"><span data-stu-id="c80ef-803">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="c80ef-804">Политика именования также помогает организациям развертывать сайты групп для их классификации по отделам.</span><span class="sxs-lookup"><span data-stu-id="c80ef-804">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

- <span data-ttu-id="c80ef-805">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="c80ef-805">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="c80ef-806">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="c80ef-806">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="c80ef-807">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="c80ef-807">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="c80ef-808">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="c80ef-808">Outlook now detects this and helps you get connected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c80ef-809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-809">PowerPoint</span></span>

- <span data-ttu-id="c80ef-810">**Быстрое взаимодействие в реальном времени в PowerPoint:** Быстрое сотрудничество в реальном времени в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c80ef-810">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="c80ef-811">**Новое расположение для видео из Интернета.** Сохраняйте видео в Microsoft Stream, чтобы его могли просматривать все пользователи организации.</span><span class="sxs-lookup"><span data-stu-id="c80ef-811">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="c80ef-812">Вставьте ссылку на видео и наслаждайтесь мультимедийной презентацией, размер которой составляет лишь часть от размера файла.</span><span class="sxs-lookup"><span data-stu-id="c80ef-812">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="c80ef-813">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-813">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="c80ef-814">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="c80ef-814">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="c80ef-815">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="c80ef-815">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="c80ef-816">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="c80ef-816">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="c80ef-817">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-817">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="c80ef-818">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-818">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="c80ef-819">**Улучшенные диаграммы.** Более удобное создание диаграмм от руки за счет использования улучшенных соединителей и более совершенного процесса преобразования рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="c80ef-819">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="c80ef-820">Подробнее</span><span class="sxs-lookup"><span data-stu-id="c80ef-820">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="c80ef-821">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="c80ef-821">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span><br /><span data-ttu-id="c80ef-822">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="c80ef-822">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

### <a name="word"></a><span data-ttu-id="c80ef-823">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-823">Word</span></span>

- <span data-ttu-id="c80ef-824">**Больше не нужно возвращаться в браузер.** Вы сами решаете, как открывать ссылки на документы Office: в браузере или в приложении.</span><span class="sxs-lookup"><span data-stu-id="c80ef-824">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="c80ef-825">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="c80ef-825">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c80ef-826">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-826">Office Suite</span></span>

- <span data-ttu-id="c80ef-827">**Поэтапное открытие больших файлов.** Возможность скачивать и открывать большие презентации PowerPoint, а также взаимодействовать с ними, даже если части презентации (например, большой видеофайл или изображение) еще не скачались полностью.</span><span class="sxs-lookup"><span data-stu-id="c80ef-827">**Open Large Files Incrementally:** The ability to download, open and interact with large powerpoint presentations, even if parts of the presentation (for example a large video or image) have not finished downloading yet.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="c80ef-830">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="c80ef-830">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="c80ef-831">Excel</span><span class="sxs-lookup"><span data-stu-id="c80ef-831">Excel</span></span>

- <span data-ttu-id="c80ef-832">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="c80ef-832">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="c80ef-833">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="c80ef-833">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


### <a name="onenote"></a><span data-ttu-id="c80ef-834">OneNote</span><span class="sxs-lookup"><span data-stu-id="c80ef-834">OneNote</span></span>

- <span data-ttu-id="c80ef-835">Улучшена синхронизация и стабильность службы за счет временного изменения частоты создания журналов версий страниц.</span><span class="sxs-lookup"><span data-stu-id="c80ef-835">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="c80ef-836">Улучшена синхронизация и стабильность службы за счет временного отключения перемещения страниц в корзину.</span><span class="sxs-lookup"><span data-stu-id="c80ef-836">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="c80ef-837">Для пользователей, которым нужно удалить страницу, будет отображаться диалоговое окно с вопросом, нужно ли удалить страницу окончательно.</span><span class="sxs-lookup"><span data-stu-id="c80ef-837">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="c80ef-838">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="c80ef-838">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="c80ef-839">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="c80ef-839">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="c80ef-840">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="c80ef-840">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="c80ef-841">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="c80ef-841">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="c80ef-842">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="c80ef-842">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="c80ef-843">Информирование пользователей с помощью информационной панели о временных изменениях в Microsoft OneNote, помогающих улучшить синхронизацию и доступность служб при высоком уровне использования по всему миру.</span><span class="sxs-lookup"><span data-stu-id="c80ef-843">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


### <a name="outlook"></a><span data-ttu-id="c80ef-844">Outlook</span><span class="sxs-lookup"><span data-stu-id="c80ef-844">Outlook</span></span>

- <span data-ttu-id="c80ef-845">Устранена проблема, из-за которой пользователи могли видеть процесс Outlook, задерживающийся в диспетчере задач после выхода.</span><span class="sxs-lookup"><span data-stu-id="c80ef-845">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>


- <span data-ttu-id="c80ef-846">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки на мыши.</span><span class="sxs-lookup"><span data-stu-id="c80ef-846">Addressed an issue that caused users to occasionally experience a crash when using the button on their mouse.</span></span>


- <span data-ttu-id="c80ef-847">Устранена проблема, из-за которой у пользователей возникали сбои в сторонних приложениях MAPI.</span><span class="sxs-lookup"><span data-stu-id="c80ef-847">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>


- <span data-ttu-id="c80ef-848">Устранена проблема, приводившая к сбою Outlook при открытии MSG или OFT-файлов, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="c80ef-848">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="c80ef-849">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="c80ef-849">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="c80ef-850">Устранена проблема, приводившая к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="c80ef-850">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


### <a name="project"></a><span data-ttu-id="c80ef-851">Project</span><span class="sxs-lookup"><span data-stu-id="c80ef-851">Project</span></span>

- <span data-ttu-id="c80ef-852">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="c80ef-852">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="c80ef-853">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="c80ef-853">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="c80ef-854">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="c80ef-854">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="c80ef-855">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, была ли задача деактивирована или активирована с помощью кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="c80ef-855">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="c80ef-856">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="c80ef-856">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="c80ef-857">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="c80ef-857">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="c80ef-858">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="c80ef-858">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="c80ef-859">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="c80ef-859">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


### <a name="word"></a><span data-ttu-id="c80ef-860">Word</span><span class="sxs-lookup"><span data-stu-id="c80ef-860">Word</span></span>

- <span data-ttu-id="c80ef-861">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="c80ef-861">Addresses an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c80ef-862">Набор Office</span><span class="sxs-lookup"><span data-stu-id="c80ef-862">Office Suite</span></span>

- <span data-ttu-id="c80ef-863">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="c80ef-863">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="c80ef-864">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="c80ef-864">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ КОНЕЦ)

> [!NOTE]
> <span data-ttu-id="c80ef-868">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="c80ef-868">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13029.20534|version-2007-september-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13001.20520|version-2006-august-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.12827.20538|version-2005-july-14|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)