---
title: Заметки о выпусках Актуального канала в 2020 г.
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Monthly Channel для подписки "Приложения Microsoft 365" в 2020 г. для ИТ-специалистов.
ms.openlocfilehash: d47124846cd605174e6ca23e26cd0e61bb5cf779
ms.sourcegitcommit: d03cdba884e24c4122db59bd06176ae5273d16e4
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/04/2020
ms.locfileid: "48878923"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a><span data-ttu-id="ed146-103">Заметки о выпусках Актуального канала в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="ed146-103">Release notes for Current Channel releases in 2020</span></span>

<span data-ttu-id="ed146-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Актуальный канал в 2020 г. для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="ed146-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="ed146-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="ed146-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="ed146-107">Мы часто выпускаем функции (а иногда даже исправления) для Актуального канала по истечении определенного времени.</span><span class="sxs-lookup"><span data-stu-id="ed146-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="ed146-108">Если у вас пока нет каких-либо из перечисленных ниже возможностей, они скоро появятся.</span><span class="sxs-lookup"><span data-stu-id="ed146-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="ed146-109">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="ed146-110">Функции Microsoft Teams могут отличаться от последних версий актуального канала, поскольку они выпускаются чаще.</span><span class="sxs-lookup"><span data-stu-id="ed146-110">Microsoft Teams features may differ from the latest Current Channel released as they have a more frequent release cadence.</span></span>




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2010-october-27"></a><span data-ttu-id="ed146-113">Версия 2010: 27 октября</span><span class="sxs-lookup"><span data-stu-id="ed146-113">Version 2010: October 27</span></span>
<span data-ttu-id="ed146-114">*Версия 2010 (сборка 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="ed146-114">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-116">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-116">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ed146-117">Access</span><span class="sxs-lookup"><span data-stu-id="ed146-117">Access</span></span>

- <span data-ttu-id="ed146-118">**Более высокая точность расширенных типов данных времени и дат.** Представляем новые и улучшенные типы данных.</span><span class="sxs-lookup"><span data-stu-id="ed146-118">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="ed146-119">Чтобы повысить совместимость синтаксиса с SQL, а также точность и уровень детализации записей, включающих даты и время, мы реализуем новый тип данных DateTime2 в Access.</span><span class="sxs-lookup"><span data-stu-id="ed146-119">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="ed146-120">Этот тип данных будет включать больший диапазон дат (с 01.01.0001 по 31.12.9999) и более точное время (в наносекундах, а не секундах), с которыми вы сможете выполнять необходимые вычисления.</span><span class="sxs-lookup"><span data-stu-id="ed146-120">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="ed146-121">Чтобы включить новый тип, установите флажок "Новое поле" > "Расширенный формат даты и времени".</span><span class="sxs-lookup"><span data-stu-id="ed146-121">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="ed146-122">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-122">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="ed146-123">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-123">Excel</span></span>

- <span data-ttu-id="ed146-124">**Создание типов данных с помощью Power Query.** Создавайте типы сложных данных с помощью Power Query из любого источника данных.</span><span class="sxs-lookup"><span data-stu-id="ed146-124">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span> [<span data-ttu-id="ed146-125">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-125">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="ed146-126">Дополнительные сведения см. в этой [записи блога](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span><span class="sxs-lookup"><span data-stu-id="ed146-126">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="ed146-127">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ed146-127">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ed146-128">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ed146-128">No conversion required.</span></span><br /><span data-ttu-id="ed146-129">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ed146-129">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="ed146-130">**Быстрые изменения с помощью пера действий.** С помощью пера действий вы можете писать от руки прямо в ячейках и использовать рукописный ввод для беглой записи данных, чтобы автоматически преобразовывать их в данные Excel.</span><span class="sxs-lookup"><span data-stu-id="ed146-130">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-131">Outlook</span></span>

- <span data-ttu-id="ed146-132">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ed146-132">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ed146-133">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ed146-133">No conversion required.</span></span><br /><span data-ttu-id="ed146-134">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ed146-134">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="ed146-135">**Проверка грамматики всегда под рукой.** Outlook помечает грамматические ошибки по мере ввода текста, так что вы можете применять исправления одним щелчком.</span><span class="sxs-lookup"><span data-stu-id="ed146-135">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="ed146-136">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-136">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="ed146-137">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="ed146-137">See details in [blog post](https://insider.office.com/ru-RU/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-138">PowerPoint</span></span>

- <span data-ttu-id="ed146-139">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ed146-139">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ed146-140">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ed146-140">No conversion required.</span></span><br /><span data-ttu-id="ed146-141">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ed146-141">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="ed146-142">Teams</span><span class="sxs-lookup"><span data-stu-id="ed146-142">Teams</span></span>

- <span data-ttu-id="ed146-143">**Шаблоны в Microsoft Teams.** Благодаря шаблонам в Teams пользователи могут выбирать из разнообразных настраиваемых вариантов при создании новой команды, что помогает быстрее начать работу.</span><span class="sxs-lookup"><span data-stu-id="ed146-143">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="ed146-144">ИТ-специалисты также могут создавать настраиваемые шаблоны для своей организации, что позволяет им стандартизировать структуры команд, демонстрировать важные приложения и масштабировать рекомендации.</span><span class="sxs-lookup"><span data-stu-id="ed146-144">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="ed146-145">**Закрепленные записи.** Эта функция позволяет пользователям "закреплять" любые сообщения канала в области сведений для просмотра всеми участниками канала.</span><span class="sxs-lookup"><span data-stu-id="ed146-145">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="ed146-146">Любой участник, у которого есть доступ к каналу, сможет видеть закрепленные сообщения.</span><span class="sxs-lookup"><span data-stu-id="ed146-146">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="ed146-147">Любой участник канала сможет закрепить любое сообщение (если эта функция не отключена с помощью параметров модерации канала).</span><span class="sxs-lookup"><span data-stu-id="ed146-147">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="ed146-148">**Отправка в каталог приложений.** Вы увидите ссылку "Отправить в каталог приложений" в левом нижнем углу экрана.</span><span class="sxs-lookup"><span data-stu-id="ed146-148">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="ed146-149">Это дополнительное место, где вы можете отправить приложения на утверждение, помимо App Studio и Visual Studio.</span><span class="sxs-lookup"><span data-stu-id="ed146-149">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="ed146-150">**Использование приложения Freehand by Invision в качестве доски во всплывающем интерфейсе собрания.** Теперь вы можете использовать приложение Freehand by Invision в качестве доски во всплывающем интерфейсе любого проводимого собрания.</span><span class="sxs-lookup"><span data-stu-id="ed146-150">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="ed146-151">Легко начинайте мозговой штурм, выбрав приложение Freehand в панели общего содержимого, установите его и запустите сеанс использования доски с коллегами!</span><span class="sxs-lookup"><span data-stu-id="ed146-151">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="ed146-152">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-152">Word</span></span>

- <span data-ttu-id="ed146-153">**Вставьте фотографии с вашего iPhone прямо в Office:** HEIC фотографии с вашего телефона теперь можно вставлять в Office.</span><span class="sxs-lookup"><span data-stu-id="ed146-153">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="ed146-154">Преобразование не требуется.</span><span class="sxs-lookup"><span data-stu-id="ed146-154">No conversion required.</span></span><br /><span data-ttu-id="ed146-155">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="ed146-155">See details in [blog post](https://insider.office.com/ru-RU/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-158">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-158">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-159">Доступ</span><span class="sxs-lookup"><span data-stu-id="ed146-159">Access</span></span>

- <span data-ttu-id="ed146-160">Исправлена проблема, из-за которой использование DAO из приложений, отличных от Office, приводило к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="ed146-160">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-161">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-161">Outlook</span></span>

- <span data-ttu-id="ed146-162">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="ed146-162">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="ed146-163">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="ed146-163">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="ed146-164">Исправлена проблема, из-за которой в Outlook создавалась вторая пустая подпись для пользователей, включивших облачные параметры.</span><span class="sxs-lookup"><span data-stu-id="ed146-164">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="ed146-165">Исправлена проблема, из-за которой облачные параметры не включались по умолчанию для пользователей.</span><span class="sxs-lookup"><span data-stu-id="ed146-165">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="ed146-166">Исправлена проблема, из-за которой не сохранялись изменения, внесенные в подпись пользователя.</span><span class="sxs-lookup"><span data-stu-id="ed146-166">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ed146-167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-167">PowerPoint</span></span>

- <span data-ttu-id="ed146-168">Устранена проблема, из-за которой сообщения о сохранении отображались в цикле при закрытии документа с рабочей надстройкой, прослушивающей событие PresentationBeforeClose и проверяющей свойство Presentation.Saved как часть обработчика событий.</span><span class="sxs-lookup"><span data-stu-id="ed146-168">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="ed146-169">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-169">Project</span></span>

- <span data-ttu-id="ed146-170">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="ed146-170">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="ed146-171">Исправлена проблема, из-за которой Project мог неожиданно прекращать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="ed146-171">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="ed146-172">Исправлена проблема, из-за которой при сохранении проекта из PWA в локальный MPP-файл запускалось событие ProjectBeforeTaskChangeEvent для данных, которые не были изменены пользователем.</span><span class="sxs-lookup"><span data-stu-id="ed146-172">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="ed146-173">Устранена проблема, из-за которой свойство NewVal в событии ProjectBeforeTaskChange имело неправильное значение в случае изменения задержки в представлении типа "Форма задачи".</span><span class="sxs-lookup"><span data-stu-id="ed146-173">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-174">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-174">Office Suite</span></span>

- <span data-ttu-id="ed146-175">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="ed146-175">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="ed146-176">Сообщения будут изменены на "Мало тонера/чернил" и "Нет тонера/чернил".</span><span class="sxs-lookup"><span data-stu-id="ed146-176">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>

- <span data-ttu-id="ed146-177">Исправлена проблема для коммерческих пользователей, применяющих System Center Configuration Manager или другие средства управления для обновления Office с использованием защиты от потери данных в конечной точке Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="ed146-177">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-october-21"></a><span data-ttu-id="ed146-179">Версия 2009: 21 октября</span><span class="sxs-lookup"><span data-stu-id="ed146-179">Version 2009: October 21</span></span>
<span data-ttu-id="ed146-180">*Версия 2009 (сборка 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="ed146-180">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-182">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-182">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ed146-183">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-183">Outlook</span></span>

- <span data-ttu-id="ed146-184">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="ed146-184">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="ed146-185">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="ed146-185">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="ed146-186">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке были нечитаемыми при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="ed146-186">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ed146-187">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-187">PowerPoint</span></span>

- <span data-ttu-id="ed146-188">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="ed146-188">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-october-13"></a><span data-ttu-id="ed146-190">Версия 2009: 13 октября</span><span class="sxs-lookup"><span data-stu-id="ed146-190">Version 2009: October 13</span></span>
<span data-ttu-id="ed146-191">*Версия 2009 (сборка 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="ed146-191">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="ed146-192">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-192">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-194">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-194">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="ed146-195">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-195">Project</span></span>

- <span data-ttu-id="ed146-196">Исправлена проблема, из-за которой Project мог аварийно завершать работу при открытии файлов, если контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="ed146-196">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-october-08"></a><span data-ttu-id="ed146-198">Версия 2009: 8 октября</span><span class="sxs-lookup"><span data-stu-id="ed146-198">Version 2009: October 08</span></span>
<span data-ttu-id="ed146-199">*Версия 2009 (сборка 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="ed146-199">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-201">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-201">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ed146-202">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-202">Outlook</span></span>

- <span data-ttu-id="ed146-203">Решает проблему, в результате которой при поиске в некэшированных общих календарях не возвращалось результатов.</span><span class="sxs-lookup"><span data-stu-id="ed146-203">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="ed146-204">Решает проблему, при которой у некоторых пользователей Outlook неожиданно запускался в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="ed146-204">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="ed146-205">Решает проблему, которая приводила к появлению периодических отказов при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="ed146-205">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ed146-206">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-206">PowerPoint</span></span>

- <span data-ttu-id="ed146-207">Установка исправления безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="ed146-207">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-208">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="ed146-208">Office Suite</span></span>

- <span data-ttu-id="ed146-209">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение «Мало тонера» или «Нет тонера», несмотря на то, что в струйных принтерах нет тонера.</span><span class="sxs-lookup"><span data-stu-id="ed146-209">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="ed146-210">Сообщения будут изменены на «Мало тонера/чернил» и «Нет тонера/чернил».</span><span class="sxs-lookup"><span data-stu-id="ed146-210">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2009-september-28"></a><span data-ttu-id="ed146-212">Версия 2009: 28 сентября</span><span class="sxs-lookup"><span data-stu-id="ed146-212">Version 2009: September 28</span></span>
<span data-ttu-id="ed146-213">*Версия 2009 (сборка 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="ed146-213">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-215">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-215">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-216">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-216">Excel</span></span>

- <span data-ttu-id="ed146-217">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="ed146-217">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="ed146-218">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-218">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="ed146-219">**Получение данных организации из Power BI с помощью типов данных.** Типы данных Excel из Power BI теперь развертываются для участников программы предварительной оценки в организациях с Office 365 E5/A5 или Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="ed146-219">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="ed146-220">Получение необходимой информации и легкость ее обновления чрезвычайно важны для многих повседневных рабочих процессов.</span><span class="sxs-lookup"><span data-stu-id="ed146-220">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="ed146-221">Мы предоставляем вам доступ к информации вашей компании или организации из Power BI как типа данных Excel, что расширяет ваши возможности получения связанных данных для электронных таблиц.</span><span class="sxs-lookup"><span data-stu-id="ed146-221">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="ed146-222">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-222">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="ed146-223">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="ed146-223">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="ed146-224">**Создание переменных для использования в формулах.** Повышайте производительность, удобочитаемость и компонуемость с помощью функции ПУСТЬ.</span><span class="sxs-lookup"><span data-stu-id="ed146-224">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="ed146-225">Эта функция позволяет создавать именованные переменные в новых или уже существующих формулах.</span><span class="sxs-lookup"><span data-stu-id="ed146-225">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="ed146-226">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-226">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="ed146-227">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="ed146-227">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-228">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-228">Outlook</span></span>

- <span data-ttu-id="ed146-229">**Автоматическое расширение поискового архива в Интернете:** включение автоматического развертывания поискового архива в Интернете</span><span class="sxs-lookup"><span data-stu-id="ed146-229">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="ed146-230">**Новая карточка профиля в Outlook.** Новая карточка профиля в Outlook включает улучшенное представление организации и соответствует стилю карточек Outlook Web.</span><span class="sxs-lookup"><span data-stu-id="ed146-230">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="ed146-231">Teams</span><span class="sxs-lookup"><span data-stu-id="ed146-231">Teams</span></span>

- <span data-ttu-id="ed146-232">**Совместное использование файлов в Microsoft Teams:**[Подробнее](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="ed146-232">**Sharing files in Microsoft Teams:** [Learn more](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-235">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-235">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ed146-236">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-236">Outlook</span></span>

- <span data-ttu-id="ed146-237">Решает проблему, из-за которой некоторые автоматически созданные сообщения электронной почты отправляются без текста сообщения, если в строке темы письма она не указана.</span><span class="sxs-lookup"><span data-stu-id="ed146-237">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ed146-238">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-238">PowerPoint</span></span>

- <span data-ttu-id="ed146-239">Исправлена проблема, из-за которой замедлялось совместное редактирование файлов, содержащих большие количества определенного типа объекта данных (E2o).</span><span class="sxs-lookup"><span data-stu-id="ed146-239">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="ed146-240">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-240">Project</span></span>

- <span data-ttu-id="ed146-241">Исправлена проблема, из-за которой при выполнении кода события и попытке внести изменения в представление формы задачи при нажатии кнопки "ОК" изменения не сохраняются.</span><span class="sxs-lookup"><span data-stu-id="ed146-241">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="ed146-242">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-242">Word</span></span>

- <span data-ttu-id="ed146-243">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="ed146-243">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-244">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-244">Office Suite</span></span>

- <span data-ttu-id="ed146-245">Это изменение исправляет проблему, связанную с функцией экспорта в GIF с анимацией, когда не выполнялся экспорт при нажатии кнопки "Экспорт".</span><span class="sxs-lookup"><span data-stu-id="ed146-245">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="ed146-246">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="ed146-246">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-22"></a><span data-ttu-id="ed146-248">Версия 2008: 22 сентября</span><span class="sxs-lookup"><span data-stu-id="ed146-248">Version 2008: September 22</span></span>
<span data-ttu-id="ed146-249">*Версия 2008 (сборка 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="ed146-249">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-251">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-251">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-252">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-252">Excel</span></span>

- <span data-ttu-id="ed146-253">Исправлена проблема, из-за которой Excel мог аварийно завершать работу при использовании экспресс-анализа после закрепления верхней строки листа.</span><span class="sxs-lookup"><span data-stu-id="ed146-253">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="ed146-254">Исправлена проблема, которая могла вызывать предупреждение о поврежденной книге, если она содержала формулы с ЕСНД().</span><span class="sxs-lookup"><span data-stu-id="ed146-254">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-255">Outlook</span></span>

- <span data-ttu-id="ed146-256">Исправлена проблема, из-за которой пользователи не могли закрыть общие календари, щелкнув значок "X" в углу.</span><span class="sxs-lookup"><span data-stu-id="ed146-256">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="ed146-257">Исправлена проблема с производительностью при отправке вложений.</span><span class="sxs-lookup"><span data-stu-id="ed146-257">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ed146-258">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-258">PowerPoint</span></span>

- <span data-ttu-id="ed146-259">Исправлена проблема, которая приводила к сбою в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-259">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="ed146-260">Visio</span><span class="sxs-lookup"><span data-stu-id="ed146-260">Visio</span></span>

- <span data-ttu-id="ed146-261">Пользователи сообщают о сбоях динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="ed146-261">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="ed146-262">Самый распространенный сбой в вилке за июль.</span><span class="sxs-lookup"><span data-stu-id="ed146-262">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="ed146-263">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-263">Word</span></span>

- <span data-ttu-id="ed146-264">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="ed146-264">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-265">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-265">Office Suite</span></span>

- <span data-ttu-id="ed146-266">Исправлена высокая загрузка ЦП при простое с использованием GIF или анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="ed146-266">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-september-09"></a><span data-ttu-id="ed146-268">Версия 2008: 9 сентября</span><span class="sxs-lookup"><span data-stu-id="ed146-268">Version 2008: September 09</span></span>
<span data-ttu-id="ed146-269">*Версия 2008 (сборка 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="ed146-269">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-271">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-271">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-272">Access</span><span class="sxs-lookup"><span data-stu-id="ed146-272">Access</span></span>

- <span data-ttu-id="ed146-273">Это изменение исправляет проблему, из-за которой Access мог аварийно завершать работу при запуске функции масштаба (SHIFT+F2) для редактирования текста.</span><span class="sxs-lookup"><span data-stu-id="ed146-273">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="ed146-274">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-274">Excel</span></span>

- <span data-ttu-id="ed146-275">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="ed146-275">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="ed146-276">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-276">Word</span></span>

- <span data-ttu-id="ed146-277">Устранена проблема, из-за которой пользователь мог потерять контент при изменении размера фигуры.</span><span class="sxs-lookup"><span data-stu-id="ed146-277">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="ed146-278">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="ed146-278">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-279">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-279">Office Suite</span></span>

- <span data-ttu-id="ed146-280">Это изменение устраняет проблему, из-за которой диалоговое окно "Сжатие рисунка" не сохраняло определенные пользовательские параметры.</span><span class="sxs-lookup"><span data-stu-id="ed146-280">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-august-31"></a><span data-ttu-id="ed146-282">Версия 2008: 31 августа</span><span class="sxs-lookup"><span data-stu-id="ed146-282">Version 2008: August 31</span></span>
<span data-ttu-id="ed146-283">*Версия 2008 (сборка 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="ed146-283">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-285">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-285">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-286">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-286">Excel</span></span>

- <span data-ttu-id="ed146-287">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="ed146-287">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="ed146-288">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="ed146-288">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="ed146-289">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="ed146-289">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="ed146-290">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-290">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="ed146-291">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-291">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="ed146-292">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="ed146-292">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-293">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-293">Outlook</span></span>

- <span data-ttu-id="ed146-294">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="ed146-294">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="ed146-295">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="ed146-295">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="ed146-296">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-296">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="ed146-297">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="ed146-297">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="ed146-298">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-298">PowerPoint</span></span>

- <span data-ttu-id="ed146-299">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="ed146-299">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="ed146-300">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="ed146-300">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="ed146-301">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="ed146-301">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="ed146-302">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-302">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="ed146-303">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-303">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="ed146-304">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="ed146-304">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="ed146-305">Teams</span><span class="sxs-lookup"><span data-stu-id="ed146-305">Teams</span></span>

- <span data-ttu-id="ed146-306">**Объединение звонков.** Функция объединения звонков дает пользователям возможность объединить активный неудерживаемый личный звонок с другим личным или групповым звонком.</span><span class="sxs-lookup"><span data-stu-id="ed146-306">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="ed146-307">Она используется для вызовов VOIP и звонков по ТСОП в Teams.</span><span class="sxs-lookup"><span data-stu-id="ed146-307">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="ed146-308">**Администраторы могут настраивать состояние присутствия с учетом смены ("На смене", "Вне смены") для сотрудников без компьютеров.** Администраторы могут настраивать состояние присутствия с учетом смены для сотрудников без компьютеров: "На смене", "Занят" (можно включить, если сотрудник на смене) и "Вне смены".</span><span class="sxs-lookup"><span data-stu-id="ed146-308">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="ed146-309">**Голосовые навыки Кортаны в Teams.** С помощью голосовых навыков Кортаны в мобильном приложении Teams пользователи могут выполнять задачи, связанные с собраниями, коммуникацией и совместной работой, используя естественный язык речи.</span><span class="sxs-lookup"><span data-stu-id="ed146-309">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="ed146-310">Пользователи могут разговаривать с Кортаной, нажав кнопку с микрофоном в приложении Teams, и делать запросы, такие как "Позвонить Марте" или "Отправить сообщение для следующего собрания", если им нужно связаться с пользователем, когда они заняты домашней работой, выгуливают собаку или в дороге.</span><span class="sxs-lookup"><span data-stu-id="ed146-310">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="ed146-311">Пользователи могут присоединиться к собранию, просто сказав: "Присоединиться к следующему собранию", или проверить свой календарь, спросив "Что у меня запланировано сегодня утром".</span><span class="sxs-lookup"><span data-stu-id="ed146-311">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="ed146-312">Находясь на собрании или во время звонка можно вызывать Кортану в меню переполнения и выполнять типичные задачи, возникающие во время собрания, например добавлять пользователей по имени или номеру ("Добавить Марту к звонку"), проводить презентацию слайдов ("Провести презентацию ежеквартальной проверки") или переходить по слайдам ("Перейти на слайд приложения").</span><span class="sxs-lookup"><span data-stu-id="ed146-312">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="ed146-313">Эта возможность также обеспечивает поиск файлов и предоставление общего доступа к ним, а также поиск и навигацию в приложении Teams ("Открыть мой чат с Николаем", "Перейти к непрочитанным действиям", "Перейти к упоминаниям" и т. д.).</span><span class="sxs-lookup"><span data-stu-id="ed146-313">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="ed146-314">Кортана в Teams соответствует требованиям конфиденциальности, безопасности и соответствия корпоративного уровня для корпоративных служб Кортаны, изложенным в [условиях использования веб-служб (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span><span class="sxs-lookup"><span data-stu-id="ed146-314">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="ed146-315">**Увеличение количества участников группового чата.** Теперь 250 пользователей могут участвовать в групповом чате Teams.</span><span class="sxs-lookup"><span data-stu-id="ed146-315">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="ed146-316">**Расстановка тегов по сменам.** В рамках этой возможности пользователям автоматически назначаются теги, соответствующие названию группы расписания и группы смены в [приложении "Смены"](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) в Teams.</span><span class="sxs-lookup"><span data-stu-id="ed146-316">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-317">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-317">Word</span></span>

- <span data-ttu-id="ed146-318">**Сохранение в закрепленных папках.** Закрепление папок облегчает сохранение файлов Office.</span><span class="sxs-lookup"><span data-stu-id="ed146-318">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="ed146-319">Мы получили отзывы о том, что пользователи хотят больше контролировать папки, доступные при сохранении нового файла.</span><span class="sxs-lookup"><span data-stu-id="ed146-319">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="ed146-320">Мы рады предоставить вам новую возможность: закрепить папки в диалоговом окне "Сохранить".</span><span class="sxs-lookup"><span data-stu-id="ed146-320">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="ed146-321">Эта новая возможность упростит сохранение файлов Word, Excel и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-321">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="ed146-322">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-322">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="ed146-323">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="ed146-323">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="ed146-324">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-324">Office Suite</span></span>

- <span data-ttu-id="ed146-325">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="ed146-325">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="ed146-326">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="ed146-326">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="ed146-327">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="ed146-327">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-330">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-330">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-331">Доступ</span><span class="sxs-lookup"><span data-stu-id="ed146-331">Access</span></span>

- <span data-ttu-id="ed146-332">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="ed146-332">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-333">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-333">Outlook</span></span>

- <span data-ttu-id="ed146-334">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="ed146-334">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="ed146-335">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="ed146-335">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="ed146-336">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="ed146-336">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="ed146-337">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="ed146-337">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="ed146-338">Исправлена проблема, из-за которой возникали периодические сбои при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="ed146-338">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="ed146-339">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="ed146-339">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="ed146-340">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="ed146-340">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="ed146-341">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="ed146-341">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="ed146-342">Решена проблема, из-за которой страница помощника по планированию не отображалась для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="ed146-342">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="ed146-343">Исправлена проблема, из-за которой возникали периодические сбои при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="ed146-343">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="ed146-344">Исправлена проблема, из-за которой возникали аномалии при использовании компактного представления.</span><span class="sxs-lookup"><span data-stu-id="ed146-344">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="ed146-345">Устранена проблема, из-за которой контекстное меню не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="ed146-345">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="ed146-346">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="ed146-346">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="ed146-347">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="ed146-347">Do you want to download them anyway?</span></span> <span data-ttu-id="ed146-348">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="ed146-348">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="ed146-349">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-349">Project</span></span>

- <span data-ttu-id="ed146-350">Исправлена проблема, из-за которой дата окончания проекта не обновляется для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-350">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="ed146-351">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="ed146-351">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="ed146-352">Skype</span><span class="sxs-lookup"><span data-stu-id="ed146-352">Skype</span></span>

- <span data-ttu-id="ed146-353">Цвет кожи танцующего смайлика изменен на нейтральный.</span><span class="sxs-lookup"><span data-stu-id="ed146-353">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-354">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-354">Word</span></span>

- <span data-ttu-id="ed146-355">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="ed146-355">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="ed146-356">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec</span><span class="sxs-lookup"><span data-stu-id="ed146-356">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-august-25"></a><span data-ttu-id="ed146-358">Версия 2007: 25 августа</span><span class="sxs-lookup"><span data-stu-id="ed146-358">Version 2007: August 25</span></span>
<span data-ttu-id="ed146-359">*Версия 2007 (сборка 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="ed146-359">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-361">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-361">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-362">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-362">Excel</span></span>

- <span data-ttu-id="ed146-363">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="ed146-363">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-364">Outlook</span></span>

- <span data-ttu-id="ed146-365">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="ed146-365">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="ed146-366">Устранена проблема, из-за которой у пользователей Outlook возникали проблемы с навигацией в компактных представлениях.</span><span class="sxs-lookup"><span data-stu-id="ed146-366">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ed146-367">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-367">PowerPoint</span></span>

- <span data-ttu-id="ed146-368">Устранена проблема со сбоем в приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-368">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="ed146-369">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-369">Word</span></span>

- <span data-ttu-id="ed146-370">Устранена проблема, из-за которой у пользователей возникали сбои при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="ed146-370">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-371">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-371">Office Suite</span></span>

- <span data-ttu-id="ed146-372">Старая область общего доступа, не основанная на веб-службе, при закрытии документа могла вызывать сбой, если область общего доступа была открыта.</span><span class="sxs-lookup"><span data-stu-id="ed146-372">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="ed146-373">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="ed146-373">This is now fixed.</span></span>


- <span data-ttu-id="ed146-374">Исправлена проблема, из-за которой пользователи видели элементы или содержимое пользовательского интерфейса, которое не отображается при определенных условиях. В частности, при входе или выходе из режима докладчика и использовании нескольких мониторов.</span><span class="sxs-lookup"><span data-stu-id="ed146-374">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-august-11"></a><span data-ttu-id="ed146-376">Версия 2007: 11 августа</span><span class="sxs-lookup"><span data-stu-id="ed146-376">Version 2007: August 11</span></span>
<span data-ttu-id="ed146-377">*Версия 2007 (сборка 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="ed146-377">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="ed146-378">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-378">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-380">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-380">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ed146-381">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-381">Outlook</span></span>

- <span data-ttu-id="ed146-382">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="ed146-382">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="ed146-383">Устранена проблема, которая иногда приводила к аварийному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="ed146-383">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="ed146-384">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-384">Project</span></span>

- <span data-ttu-id="ed146-385">Исправлена проблема, из-за которой проект в нерабочем состоянии нельзя было открыть.</span><span class="sxs-lookup"><span data-stu-id="ed146-385">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2007-july-30"></a><span data-ttu-id="ed146-387">Версия 2007: 30 июля</span><span class="sxs-lookup"><span data-stu-id="ed146-387">Version 2007: July 30</span></span>
<span data-ttu-id="ed146-388">*Версия 2007 (сборка 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="ed146-388">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-390">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-390">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-391">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-391">Excel</span></span>

- <span data-ttu-id="ed146-392">**Связь с PDF.** Связывайте с PDF, импортируйте, обновляйте данные из PDF.</span><span class="sxs-lookup"><span data-stu-id="ed146-392">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="ed146-393">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-393">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="ed146-394">**Фильтруйте и сортируйте, не мешая другим:** Теперь вы можете сортировать и фильтровать файлы Excel во время совместной работы с другими пользователями в представлении листа.</span><span class="sxs-lookup"><span data-stu-id="ed146-394">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="ed146-395">Благодаря этой новой функции вам не будет мешать выполняемая другими пользователями сортировка и фильтрация при совместной работе с документом.</span><span class="sxs-lookup"><span data-stu-id="ed146-395">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="ed146-396">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-396">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="ed146-397">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="ed146-397">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="ed146-398">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="ed146-398">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="ed146-399">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="ed146-399">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="ed146-400">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="ed146-400">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="ed146-401">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-401">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="ed146-402">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="ed146-402">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-403">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-403">Outlook</span></span>

- <span data-ttu-id="ed146-404">**Создание опросов в Outlook с помощью быстрого опроса.** Можно легко создать опрос, собрать голоса и просмотреть результаты в сообщении электронной почты. [Подробнее](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="ed146-404">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="ed146-405">**Сохраняйте свои фотографии с высокой точностью при отправке их как части электронного письма:** Доступен новый параметр Outlook для ограничения сжатия изображений при отправке изображений как части содержимого электронной почты.</span><span class="sxs-lookup"><span data-stu-id="ed146-405">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="ed146-406">**Быстрое повторное открытие элементов из предыдущего сеанса.** Добавлена возможность быстро открывать элементы из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="ed146-406">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="ed146-407">После нормального или аварийного завершения работы Outlook при повторном открытии приложения можно быстро перезапустить его элементы.</span><span class="sxs-lookup"><span data-stu-id="ed146-407">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="ed146-408">По умолчанию эта функция включена.</span><span class="sxs-lookup"><span data-stu-id="ed146-408">This feature is on by default.</span></span> <span data-ttu-id="ed146-409">Чтобы ее отключить, выберите "Параметры > Общие > Параметры запуска".</span><span class="sxs-lookup"><span data-stu-id="ed146-409">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-410">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-410">PowerPoint</span></span>

- <span data-ttu-id="ed146-411">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="ed146-411">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="ed146-412">Teams</span><span class="sxs-lookup"><span data-stu-id="ed146-412">Teams</span></span>

- <span data-ttu-id="ed146-413">**Новые упрощенные параметры уведомлений:** Пользователи теперь могут управлять параметрами уведомлений более простым способом с улучшенными возможностями.</span><span class="sxs-lookup"><span data-stu-id="ed146-413">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="ed146-414">**В Teams теперь поддерживаются встроенные уведомления Windows:** Теперь пользователи могут выбирать предпочитаемый способ доставки уведомлений, используя команды, встроенные в баннеры или встроенные баннеры Windows.</span><span class="sxs-lookup"><span data-stu-id="ed146-414">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="ed146-415">**Панель сведений о канале:** При выборе значка "сведения о канале" в заголовке канала, открывается панель, в которой отображаются сведения о канале, в том числе описание канала, список последних участников и членов, а также новые домашнюю страницу для системных сообщений.</span><span class="sxs-lookup"><span data-stu-id="ed146-415">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="ed146-416">**Отключите предварительный просмотр уведомлений беседы.** Пользователи могут изменять параметры и управлять предварительными просмотрами для всплывающих уведомлений в беседах.</span><span class="sxs-lookup"><span data-stu-id="ed146-416">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="ed146-417">**Предложенные ответы:** Мы добавили возможность для пользователей Teams использовать предложенные ответы в их диалогах.</span><span class="sxs-lookup"><span data-stu-id="ed146-417">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="ed146-418">Эти предложения появляются в нижней части сообщения беседы, если только они включены.</span><span class="sxs-lookup"><span data-stu-id="ed146-418">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="ed146-419">Они позволяют быстро и легко отвечать на сообщения.</span><span class="sxs-lookup"><span data-stu-id="ed146-419">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="ed146-420">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-420">Word</span></span>

- <span data-ttu-id="ed146-421">**Автоматическое применение или рекомендации меток конфиденциальности.** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального содержимого.</span><span class="sxs-lookup"><span data-stu-id="ed146-421">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="ed146-422">**Сохранение текста в векторах.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Excel, Word и PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-422">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-425">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-425">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-426">Access</span><span class="sxs-lookup"><span data-stu-id="ed146-426">Access</span></span>

- <span data-ttu-id="ed146-427">Была исправлена проблема, когда при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке «Слишком сложный запрос».</span><span class="sxs-lookup"><span data-stu-id="ed146-427">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="ed146-428">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-428">Excel</span></span>

- <span data-ttu-id="ed146-429">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы возникает ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="ed146-429">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-430">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-430">Outlook</span></span>

- <span data-ttu-id="ed146-431">Устранена проблема, из-за которой пользователи CLP могут столкнуться со сбоем при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="ed146-431">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="ed146-432">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="ed146-432">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="ed146-433">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="ed146-433">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="ed146-434">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="ed146-434">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="ed146-435">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="ed146-435">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="ed146-436">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="ed146-436">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="ed146-437">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-437">Project</span></span>

- <span data-ttu-id="ed146-438">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="ed146-438">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="ed146-439">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости были скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="ed146-439">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="ed146-440">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-440">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-441">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="ed146-441">Office Suite</span></span>

- <span data-ttu-id="ed146-442">Исправлена проблема, из-за которой сообщение о процессе выполнения появлялось, даже если переход на полную версию продукта завершен.</span><span class="sxs-lookup"><span data-stu-id="ed146-442">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="ed146-443">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="ed146-443">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="ed146-444">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="ed146-444">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-july-28"></a><span data-ttu-id="ed146-446">Версия 2006: 28 июля</span><span class="sxs-lookup"><span data-stu-id="ed146-446">Version 2006: July 28</span></span>
<span data-ttu-id="ed146-447">*Версия 2006 (сборка 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="ed146-447">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-449">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-449">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-450">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-450">Excel</span></span>

- <span data-ttu-id="ed146-451">Исправлена проблема, из-за которой при загрузке книги с несколькими листами в режиме разметки страницы возникает ошибка или зависание.</span><span class="sxs-lookup"><span data-stu-id="ed146-451">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-452">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-452">Outlook</span></span>

- <span data-ttu-id="ed146-453">Мы устранили проблемы при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="ed146-453">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="ed146-454">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-454">Word</span></span>

- <span data-ttu-id="ed146-455">Мы устранили проблемы при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="ed146-455">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-456">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="ed146-456">Office Suite</span></span>

- <span data-ttu-id="ed146-457">При закрытии файлов Office мог произойти сбой из-за проблем с синхронизацией.</span><span class="sxs-lookup"><span data-stu-id="ed146-457">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-july-14"></a><span data-ttu-id="ed146-459">Версия 2006: 14 июля</span><span class="sxs-lookup"><span data-stu-id="ed146-459">Version 2006: July 14</span></span>
<span data-ttu-id="ed146-460">*Версия 2006 (сборка 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="ed146-460">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="ed146-461">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-461">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-463">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-463">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-464">Доступ</span><span class="sxs-lookup"><span data-stu-id="ed146-464">Access</span></span>

- <span data-ttu-id="ed146-465">Устранена проблема со вставкой связанных таблиц SQL, содержащих поле удостоверения (например, счетчик).</span><span class="sxs-lookup"><span data-stu-id="ed146-465">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="ed146-466">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-466">Excel</span></span>

- <span data-ttu-id="ed146-467">Для рабочих книг, доступных только для чтения, могла действовать автоматическая классификация документов.</span><span class="sxs-lookup"><span data-stu-id="ed146-467">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="ed146-468">Устранен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="ed146-468">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="ed146-469">OneNote</span><span class="sxs-lookup"><span data-stu-id="ed146-469">OneNote</span></span>

- <span data-ttu-id="ed146-470">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов.</span><span class="sxs-lookup"><span data-stu-id="ed146-470">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-471">Outlook</span></span>

- <span data-ttu-id="ed146-472">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="ed146-472">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ed146-473">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-473">Office Suite</span></span>

- <span data-ttu-id="ed146-474">Мы отправили часть AppV51 на доработку, чтобы исправить в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="ed146-474">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="ed146-475">Устранена проблема со сбоем в работе узла Office в Windows при активации надстройки, когда значение реестра TabProcGrowth относилось к типу REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="ed146-475">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2006-june-30"></a><span data-ttu-id="ed146-477">Версия 2006: 30 июня</span><span class="sxs-lookup"><span data-stu-id="ed146-477">Version 2006: June 30</span></span>
<span data-ttu-id="ed146-478">*Версия 2006 (сборка 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="ed146-478">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-480">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-480">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-481">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-481">Excel</span></span>

- <span data-ttu-id="ed146-482">**Длинные имена файлов.** Классическое приложение Excel для Windows теперь поддерживает файлы OneDrive и SharePoint с именами и путями длиной до 400 символов.</span><span class="sxs-lookup"><span data-stu-id="ed146-482">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="ed146-483">**Улучшение функции Realtimedata (RTD):** В Office 365 версии 2002 канала Monthly channel или более поздних версиях функция Excel RealTimeData (ДРВ) работает гораздо быстрее, чем в вычисление данных в таблице в Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="ed146-483">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="ed146-484">Мы удалили узкие места в базовой памяти и структурах данных, а также обеспечили потокобезопасность, чтобы разрешить вычисление во всех доступных потоках многопоточного пересчета (MTR).</span><span class="sxs-lookup"><span data-stu-id="ed146-484">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-485">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-485">Outlook</span></span>

- <span data-ttu-id="ed146-486">**Новая опция, позволяющая отключить предложения @ упоминания при составлении писем в Outlook:** Считаете ли вы средство @ упоминания более раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="ed146-486">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="ed146-487">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="ed146-487">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="ed146-488">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span><span class="sxs-lookup"><span data-stu-id="ed146-488">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="ed146-489">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="ed146-489">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="ed146-490">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-490">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="ed146-491">**Добавлены кнопки во всплывающие уведомления Outlook.** При использовании Outlook в Windows 10 кнопки быстрых действий теперь отображаются во всплывающих уведомлениях Outlook.</span><span class="sxs-lookup"><span data-stu-id="ed146-491">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-492">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-492">PowerPoint</span></span>

- <span data-ttu-id="ed146-493">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="ed146-493">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="ed146-494">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="ed146-494">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="ed146-495">Teams</span><span class="sxs-lookup"><span data-stu-id="ed146-495">Teams</span></span>

- <span data-ttu-id="ed146-496">**Номера телефонов участников конференций ТСОП скрыты от внешних пользователей.** Для клиентов, у которых включены Аудиоконференции для собраний Teams, номер телефона участника скрывается от пользователей, присоединившихся к конференции извне организации.</span><span class="sxs-lookup"><span data-stu-id="ed146-496">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="ed146-497">**Упрощенное управление параметрами уведомлений канала.** В списке групп и каналов или заголовке канала пользователи могут легко управлять параметрами уведомлений, включая и выключая все действия одним щелчком или настраивая детализированные параметры по своему усмотрению.</span><span class="sxs-lookup"><span data-stu-id="ed146-497">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="ed146-498">**Рация.** Мгновенная голосовая связь по нажатию.</span><span class="sxs-lookup"><span data-stu-id="ed146-498">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-499">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-499">Word</span></span>

- <span data-ttu-id="ed146-500">**Подтверждение действий в средстве чтения с экрана.** Подтверждение действий — это важное требование для обеспечения специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="ed146-500">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="ed146-501">С появлением нового API уведомлений из Windows мы можем оповещать пользователей средства чтения с экрана об успехе их действий.</span><span class="sxs-lookup"><span data-stu-id="ed146-501">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="ed146-502">Теперь пользователи экранного диктора в Word для Win32 уведомляются о вырезании, копировании, вставке, использовании полужирного шрифта, курсива или подчеркивания, отмене, повторе, автозамене и автоматическом использовании прописных букв.</span><span class="sxs-lookup"><span data-stu-id="ed146-502">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="ed146-503">Чтобы включить эту возможность, включите экранный диктор с помощью клавиш Windows+CTRL+ВВОД.</span><span class="sxs-lookup"><span data-stu-id="ed146-503">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-506">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-506">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-507">Доступ</span><span class="sxs-lookup"><span data-stu-id="ed146-507">Access</span></span>

- <span data-ttu-id="ed146-508">Устранена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="ed146-508">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="ed146-509">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-509">Excel</span></span>

- <span data-ttu-id="ed146-510">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="ed146-510">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-511">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-511">Outlook</span></span>

- <span data-ttu-id="ed146-512">Устранена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="ed146-512">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="ed146-513">Устранена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="ed146-513">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="ed146-514">Устранена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="ed146-514">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="ed146-515">Устранена проблема, из-за которой не выполнялось действие при нажатии CTRL и щелчка мыши при включенных параметрах облака.</span><span class="sxs-lookup"><span data-stu-id="ed146-515">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="ed146-516">Устранена проблема, из-за которой поиск возможности предложения функции не возвращал результатов, и пользователи не могли делиться идеями.</span><span class="sxs-lookup"><span data-stu-id="ed146-516">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="ed146-517">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-517">Project</span></span>

- <span data-ttu-id="ed146-518">Устранена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="ed146-518">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="ed146-519">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="ed146-519">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="ed146-520">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="ed146-520">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="ed146-521">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-521">Word</span></span>

- <span data-ttu-id="ed146-522">Устранена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="ed146-522">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-24"></a><span data-ttu-id="ed146-524">Версия 2005: 24 июня</span><span class="sxs-lookup"><span data-stu-id="ed146-524">Version 2005: June 24</span></span>
<span data-ttu-id="ed146-525">*Версия 2005 (сборка 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="ed146-525">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-527">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-527">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-528">Доступ</span><span class="sxs-lookup"><span data-stu-id="ed146-528">Access</span></span>

- <span data-ttu-id="ed146-529">Эта ошибка устранена. Теперь вы можете вызвать расширенный тип данных "Дата/время" без сбоя приложения.</span><span class="sxs-lookup"><span data-stu-id="ed146-529">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="ed146-530">Если у вас возникнут другие проблемы, сообщите команде разработчиков.</span><span class="sxs-lookup"><span data-stu-id="ed146-530">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="ed146-531">Проблема устранена. Теперь вы можете вернуться к последней версии Access и использовать DAO/VBA для изменения десятичного типа данных и управления им.</span><span class="sxs-lookup"><span data-stu-id="ed146-531">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="ed146-532">Если у вас возникнут другие проблемы с использованием нашего типа данных, сообщите команде разработчиков Access.</span><span class="sxs-lookup"><span data-stu-id="ed146-532">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="ed146-533">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-533">Excel</span></span>

- <span data-ttu-id="ed146-534">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="ed146-534">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="ed146-535">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-535">Outlook</span></span>

- <span data-ttu-id="ed146-536">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="ed146-536">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="ed146-537">Устранена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="ed146-537">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="ed146-538">Устранена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение &quot;Правила на этом компьютере противоречат правилам Microsoft Exchange&quot;.</span><span class="sxs-lookup"><span data-stu-id="ed146-538">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="ed146-539">Устранена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="ed146-539">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="ed146-540">Устранена проблема, которая в некоторых ситуациях приводила к периодическим зависаниям и сбоям.</span><span class="sxs-lookup"><span data-stu-id="ed146-540">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="ed146-541">Устранена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="ed146-541">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="ed146-542">Устранена проблема, из-за которой поиск возможности предложения функции не возвращал результатов, и пользователи не могли делиться идеями.</span><span class="sxs-lookup"><span data-stu-id="ed146-542">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ed146-543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-543">PowerPoint</span></span>

- <span data-ttu-id="ed146-544">Устранена проблема со сбоем панели предложений.</span><span class="sxs-lookup"><span data-stu-id="ed146-544">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="ed146-545">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-545">Project</span></span>

- <span data-ttu-id="ed146-546">Устранена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100 %, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="ed146-546">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-547">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-547">Word</span></span>

- <span data-ttu-id="ed146-548">Устранена проблема, которая могла вызвать сбой при перетаскивании части содержимого из приложения.</span><span class="sxs-lookup"><span data-stu-id="ed146-548">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-549">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-549">Office Suite</span></span>

- <span data-ttu-id="ed146-550">Это изменение устраняет потенциальные зависания при загрузке и воспроизведении анимированных данных, таких как GIF или трехмерные модели.</span><span class="sxs-lookup"><span data-stu-id="ed146-550">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-09"></a><span data-ttu-id="ed146-552">Версия 2005: 9 июня</span><span class="sxs-lookup"><span data-stu-id="ed146-552">Version 2005: June 09</span></span>
<span data-ttu-id="ed146-553">*Версия 2005 (сборка 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="ed146-553">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="ed146-554">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-554">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="ed146-555">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-555">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-556">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-556">Excel</span></span>

- <span data-ttu-id="ed146-557">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="ed146-557">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-558">PowerPoint</span></span>

- <span data-ttu-id="ed146-559">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="ed146-559">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-560">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-560">Word</span></span>

- <span data-ttu-id="ed146-561">**Произвольное выделение и ластик в панели инструментов рукописного ввода.** При использовании средств рисования в панели инструментов рукописного ввода теперь доступно произвольное выделение и ластик.</span><span class="sxs-lookup"><span data-stu-id="ed146-561">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-564">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-564">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-565">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-565">Excel</span></span>

- <span data-ttu-id="ed146-566">Устранена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="ed146-566">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-567">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-567">PowerPoint</span></span>

- <span data-ttu-id="ed146-568">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="ed146-568">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="ed146-569">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-569">Project</span></span>

- <span data-ttu-id="ed146-570">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="ed146-570">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ed146-571">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-571">Office Suite</span></span>

- <span data-ttu-id="ed146-572">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="ed146-572">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-02"></a><span data-ttu-id="ed146-574">Версия 2005: 2 июня</span><span class="sxs-lookup"><span data-stu-id="ed146-574">Version 2005: June 02</span></span>
<span data-ttu-id="ed146-575">*Версия 2005 (сборка 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="ed146-575">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-577">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-577">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-578">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-578">Excel</span></span>

- <span data-ttu-id="ed146-579">**Автоматическое использование новых типов данных.** При вводе значения данных, похожего на акцию или географическое положение, Excel предлагает преобразовать его в соответствующий связанный тип данных — акции или географические данные.</span><span class="sxs-lookup"><span data-stu-id="ed146-579">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="ed146-580">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-580">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="ed146-581">**Доклады с анимированными изображениями GIF.** Анимированные изображения GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="ed146-581">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-582">Outlook</span></span>

- <span data-ttu-id="ed146-583">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="ed146-583">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="ed146-584">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="ed146-584">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="ed146-585">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-585">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="ed146-586">**Доклады с анимированными изображениями GIF.** Анимированные изображения GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="ed146-586">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="ed146-587">**Обновления Календаря.** Ознакомьтесь с наглядными обновлениями, упрощающими сканирование календаря.</span><span class="sxs-lookup"><span data-stu-id="ed146-587">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="ed146-588">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-588">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="ed146-589">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="ed146-589">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-590">PowerPoint</span></span>

- <span data-ttu-id="ed146-591">**Доклады с анимированными изображениями GIF.** Анимированные изображения GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими. [Подробнее](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01).</span><span class="sxs-lookup"><span data-stu-id="ed146-591">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="ed146-592">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="ed146-592">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="ed146-593">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-593">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="ed146-594">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="ed146-594">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="ed146-595">**Переключатель не нужен: достаточно наушников.** Используйте наушники Surface для управления презентациями PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-595">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="ed146-596">Как это работает: после сопряжения необходимо включить эту функцию в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-596">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="ed146-597">Чтобы начать презентацию, нажмите клавишу F5 или выберите команду "Показ слайдов" > "С начала".</span><span class="sxs-lookup"><span data-stu-id="ed146-597">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="ed146-598">В режиме показа слайдов щелкните слайд правой кнопкой мыши и в разделе "Параметры Surface Earbuds" выберите пункт "Использование жестов для управления презентацией".</span><span class="sxs-lookup"><span data-stu-id="ed146-598">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="ed146-599">Этот параметр будет сохранен во всех будущих презентациях.</span><span class="sxs-lookup"><span data-stu-id="ed146-599">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="ed146-600">Теперь вы можете проводить вперед и назад на левом наушнике для перехода по презентациям в режиме показа слайдов.</span><span class="sxs-lookup"><span data-stu-id="ed146-600">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="ed146-601">Дважды коснитесь экрана, чтобы воспроизвести или приостановить внедренные видеоролики.</span><span class="sxs-lookup"><span data-stu-id="ed146-601">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="ed146-602">Важно! Чтобы использовать жесты для управления презентациями, необходимо связать наушники Surface с приложением Surface Audio для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="ed146-602">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="ed146-603">Инструкции о начале работы с приложением Surface Audio на Windows 10 находятся здесь.</span><span class="sxs-lookup"><span data-stu-id="ed146-603">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="ed146-604">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-604">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="ed146-605">Teams</span><span class="sxs-lookup"><span data-stu-id="ed146-605">Teams</span></span>

- <span data-ttu-id="ed146-606">**Изменения компоновки видео в собраниях Teams.** В скором времени количество участников, которых можно одновременно просматривать в собрании Teams, увеличится с 4 до 9.</span><span class="sxs-lookup"><span data-stu-id="ed146-606">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="ed146-607">**Добавление системных звуков в прямые трансляции.** Докладчики и организаторы прямых трансляций теперь могут включать системные звуки при демонстрации рабочего стола и экрана.</span><span class="sxs-lookup"><span data-stu-id="ed146-607">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="ed146-608">При этом пользователям будут слышны все звуки представляемого содержимого.</span><span class="sxs-lookup"><span data-stu-id="ed146-608">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="ed146-609">**Организаторы могут менять параметры "зала ожидания" для участников, подключившихся по телефону.** Этот параметр определяет, могут ли пользователи присоединяться непосредственно к собранию по телефону или будут попадать в "зал ожидания" независимо от параметра "Автоматически допускать пользователей".</span><span class="sxs-lookup"><span data-stu-id="ed146-609">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="ed146-610">**Поднятие руки на собраниях.** Теперь пользователи могут поднимать виртуальные руки на собраниях!</span><span class="sxs-lookup"><span data-stu-id="ed146-610">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="ed146-611">Другие участники увидят поднятую руку рядом с вашим именем на сцене собрания и в списке участников.</span><span class="sxs-lookup"><span data-stu-id="ed146-611">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="ed146-612">**Настройка фона видео собрания.** В собраниях с видео вы можете использовать различные статические фоновые изображения.</span><span class="sxs-lookup"><span data-stu-id="ed146-612">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="ed146-613">При этом будет отображаться соответствующее изображение, а не ваше настоящее окружение.</span><span class="sxs-lookup"><span data-stu-id="ed146-613">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="ed146-614">**Добавление участников в чат.** Теперь в один чат можно добавить до 350 участников.</span><span class="sxs-lookup"><span data-stu-id="ed146-614">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="ed146-615">**Значок параметров в веб-канале активности.** Теперь пользователи могут переходить непосредственно к веб-каналу активности и параметрам уведомлений из левой области канала с помощью значка параметров (шестеренки).</span><span class="sxs-lookup"><span data-stu-id="ed146-615">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="ed146-616">**Удобный доступ к параметрам собрания из активного собрания Teams.** Теперь организаторы собраний могут быстрее и проще настраивать параметры докладчика и "зала ожидания" после начала собрания Teams с помощью ссылки на панели участников.</span><span class="sxs-lookup"><span data-stu-id="ed146-616">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="ed146-617">Эта новая функция будет доступна как для запланированных, так и для срочных собраний.</span><span class="sxs-lookup"><span data-stu-id="ed146-617">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="ed146-618">**Аналитика групп и каналов.** Помимо аналитических данных о группах, теперь также можно просматривать метрики и сведения на уровне канала.</span><span class="sxs-lookup"><span data-stu-id="ed146-618">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="ed146-619">Кроме того, мы увеличили срок до 90 дней, чтобы можно было анализировать данные за более продолжительный период времени.</span><span class="sxs-lookup"><span data-stu-id="ed146-619">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="ed146-620">Этот выпуск также включает новые метрики и диаграммы количества записей, ответов и собраний группы или канала.</span><span class="sxs-lookup"><span data-stu-id="ed146-620">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="ed146-621">**Объявления о входе и выходе.** Мы добавили функцию, благодаря которой организаторы собраний могут включать и отключать объявления о входе и выходе из собрания.</span><span class="sxs-lookup"><span data-stu-id="ed146-621">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-622">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-622">Word</span></span>

- <span data-ttu-id="ed146-623">**Расшифровка аббревиатур без выхода из Word.** Когда в тексте встречается сокращение, приложение Word пытается определить его значение в соответствии с тем, как другие пользователи используют его.</span><span class="sxs-lookup"><span data-stu-id="ed146-623">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="ed146-624">**Доклады с анимированными изображениями GIF.** Анимированные изображения GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="ed146-624">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-627">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-627">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="ed146-628">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-628">Excel</span></span>

- <span data-ttu-id="ed146-629">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="ed146-629">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="ed146-630">В некоторых случаях при щелчке гиперссылки внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="ed146-630">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-631">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-631">Outlook</span></span>

- <span data-ttu-id="ed146-632">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="ed146-632">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="ed146-633">Устранена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="ed146-633">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="ed146-634">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="ed146-634">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="ed146-635">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="ed146-635">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="ed146-636">Skype</span><span class="sxs-lookup"><span data-stu-id="ed146-636">Skype</span></span>

- <span data-ttu-id="ed146-637">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="ed146-637">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="ed146-638">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="ed146-638">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="ed146-639">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="ed146-639">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ed146-640">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-640">Office Suite</span></span>

- <span data-ttu-id="ed146-641">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="ed146-641">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="ed146-642">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="ed146-642">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="ed146-643">Аварийное завершение работы узла Office в Windows, при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имеет значение "0".</span><span class="sxs-lookup"><span data-stu-id="ed146-643">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="ed146-644">Это изменение может устранить проблему.</span><span class="sxs-lookup"><span data-stu-id="ed146-644">This change would fix this issue.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-21"></a><span data-ttu-id="ed146-646">Версия 2004: 21 мая</span><span class="sxs-lookup"><span data-stu-id="ed146-646">Version 2004: May 21</span></span>
<span data-ttu-id="ed146-647">*Версия 2004 (сборка 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="ed146-647">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-649">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-649">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-650">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-650">Excel</span></span>

- <span data-ttu-id="ed146-651">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="ed146-651">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-652">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-652">Outlook</span></span>

- <span data-ttu-id="ed146-653">Устранена проблема, из-за которой у пользователей возникали сбои при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="ed146-653">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-654">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-654">Office Suite</span></span>

- <span data-ttu-id="ed146-655">Устранена проблема с технологией "нажми и работай", которая иногда приводила к сбоям при обновлении до последних сборок.</span><span class="sxs-lookup"><span data-stu-id="ed146-655">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="ed146-656">Устранена проблема в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="ed146-656">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-12"></a><span data-ttu-id="ed146-658">Версия 2004: 12 мая</span><span class="sxs-lookup"><span data-stu-id="ed146-658">Version 2004: May 12</span></span>
<span data-ttu-id="ed146-659">*Версия 2004 (сборка 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="ed146-659">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="ed146-660">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-660">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-662">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-662">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ed146-663">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-663">Outlook</span></span>

- <span data-ttu-id="ed146-664">Устранена проблема, из-за которой у пользователей возникали сбои при отображении всплывающих уведомлений.</span><span class="sxs-lookup"><span data-stu-id="ed146-664">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-04"></a><span data-ttu-id="ed146-666">Версия 2004: 04 мая</span><span class="sxs-lookup"><span data-stu-id="ed146-666">Version 2004: May 04</span></span>
<span data-ttu-id="ed146-667">*Версия 2004 (сборка 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="ed146-667">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-669">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-669">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ed146-670">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-670">Office Suite</span></span>

- <span data-ttu-id="ed146-671">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="ed146-671">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-29"></a><span data-ttu-id="ed146-673">Версия 2004: 29 апреля</span><span class="sxs-lookup"><span data-stu-id="ed146-673">Version 2004: April 29</span></span>
<span data-ttu-id="ed146-674">*Версия 2004 (сборка 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="ed146-674">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-676">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-676">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ed146-677">Access</span><span class="sxs-lookup"><span data-stu-id="ed146-677">Access</span></span>

- <span data-ttu-id="ed146-678">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="ed146-678">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="ed146-679">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="ed146-679">Search and replace text in SQL View.</span></span> <span data-ttu-id="ed146-680">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="ed146-680">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="ed146-681">**Быстрое добавление таблиц.** Используйте область задач "Добавление таблиц", которая остается открытой во время работы, чтобы добавлять таблицы в связи и запросы.</span><span class="sxs-lookup"><span data-stu-id="ed146-681">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="ed146-682">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-682">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="ed146-683">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-683">Excel</span></span>

- <span data-ttu-id="ed146-684">**Поддержка соединителя Facebook заканчивается:** Начиная с апреля 2020 года Excel больше не будет поддерживать подключения к внешним данным, которые используют соединитель Facebook.</span><span class="sxs-lookup"><span data-stu-id="ed146-684">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="ed146-685">**Есть вопросы? Спросите у Excel.** Функция "Идеи" в Excel дает возможность задавать вопросы о данных. Нет необходимости тратить время на составление формул (доступно только на английском языке).</span><span class="sxs-lookup"><span data-stu-id="ed146-685">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="ed146-686">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-686">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="ed146-687">**Новые изображения, чтобы оживить книги.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в книгах.</span><span class="sxs-lookup"><span data-stu-id="ed146-687">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="ed146-688">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="ed146-688">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="ed146-689">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-689">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="ed146-690">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-690">Outlook</span></span>

- <span data-ttu-id="ed146-691">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="ed146-691">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="ed146-692">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="ed146-692">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="ed146-693">**Новые изображения, чтобы оживить сообщения.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="ed146-693">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="ed146-694">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="ed146-694">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="ed146-695">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-695">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="ed146-696">**Поддержка рекомендаций по расположениям для повторяющихся собраний:** поиск конференц-залов при планировании повторяющихся собраний.</span><span class="sxs-lookup"><span data-stu-id="ed146-696">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-697">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-697">PowerPoint</span></span>

- <span data-ttu-id="ed146-698">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="ed146-698">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="ed146-699">**Новые изображения, чтобы оживить слайды.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в презентациях.</span><span class="sxs-lookup"><span data-stu-id="ed146-699">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="ed146-700">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="ed146-700">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="ed146-701">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-701">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="ed146-702">Teams</span><span class="sxs-lookup"><span data-stu-id="ed146-702">Teams</span></span>

- <span data-ttu-id="ed146-703">**Улучшения в календаре Teams.** Щелкните правой кнопкой мыши элемент календаря, чтобы извлечь параметры просьбы ответить, начать чат с участниками собрания или быстро присоединиться к собранию, когда оно начнется.</span><span class="sxs-lookup"><span data-stu-id="ed146-703">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="ed146-704">Мы также внесли улучшения в форму планирования события.</span><span class="sxs-lookup"><span data-stu-id="ed146-704">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="ed146-705">**Теги для вас.** Создавайте теги и назначайте их пользователям, чтобы можно было @упомянуть группу, роль, отдел и т. д. Владельцы команд, попробуйте сами.</span><span class="sxs-lookup"><span data-stu-id="ed146-705">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="ed146-706">Перейдите в команду и выберите "Дополнительные параметры > Управление тегами".</span><span class="sxs-lookup"><span data-stu-id="ed146-706">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-707">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-707">Word</span></span>

- <span data-ttu-id="ed146-708">**Инструменты всегда под рукой.** На панели элементов "Рисование" найдите интеллектуальное перо, с помощью которого к тексту можно добавить жесты рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="ed146-708">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="ed146-709">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-709">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="ed146-710">**Новые изображения, чтобы оживить документы.** Тысячи бесплатных стоковых изображений, значков и наклеек, которые можно использовать в документах.</span><span class="sxs-lookup"><span data-stu-id="ed146-710">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="ed146-711">Для начала выберите "Вставить > Рисунки > Стоковые изображения".</span><span class="sxs-lookup"><span data-stu-id="ed146-711">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="ed146-712">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-712">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-715">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-715">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-716">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-716">Excel</span></span>

- <span data-ttu-id="ed146-717">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="ed146-717">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ed146-718">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="ed146-718">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="ed146-719">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="ed146-719">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-720">Outlook</span></span>

- <span data-ttu-id="ed146-721">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="ed146-721">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="ed146-722">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="ed146-722">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="ed146-723">Устранена проблема, приводившая к сбою Outlook при открытии MSG или OFT-файлов, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="ed146-723">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="ed146-724">Устранена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="ed146-724">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="ed146-725">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="ed146-725">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="ed146-726">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-726">Project</span></span>

- <span data-ttu-id="ed146-727">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="ed146-727">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="ed146-728">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, и запятой в качестве десятичного разделителя метод добавления объектов TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="ed146-728">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ed146-729">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-729">Office Suite</span></span>

- <span data-ttu-id="ed146-730">Исправлена ошибка, из-за которой одновременно блокируется ограничение доступа и защита файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="ed146-730">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-15"></a><span data-ttu-id="ed146-732">Версия 2003:15 апреля</span><span class="sxs-lookup"><span data-stu-id="ed146-732">Version 2003: April 15</span></span>
<span data-ttu-id="ed146-733">*Версия 2003 (сборка 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="ed146-733">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="ed146-734">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="ed146-734">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="ed146-735">Версия 2003: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="ed146-735">Version 2003: April 14</span></span>
<span data-ttu-id="ed146-736">*Версия 2003 (сборка 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="ed146-736">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="ed146-737">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-737">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-739">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-739">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-740">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-740">Excel</span></span>

- <span data-ttu-id="ed146-741">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="ed146-741">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-742">Outlook</span></span>

- <span data-ttu-id="ed146-743">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="ed146-743">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="ed146-744">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-744">Project</span></span>

- <span data-ttu-id="ed146-745">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="ed146-745">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-746">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-746">Word</span></span>

- <span data-ttu-id="ed146-747">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="ed146-747">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-31"></a><span data-ttu-id="ed146-749">Версия 2003: 31 марта</span><span class="sxs-lookup"><span data-stu-id="ed146-749">Version 2003: March 31</span></span>
<span data-ttu-id="ed146-750">*Версия 2003 (сборка 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="ed146-750">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-752">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-752">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="ed146-753">OneNote</span><span class="sxs-lookup"><span data-stu-id="ed146-753">OneNote</span></span>

- <span data-ttu-id="ed146-754">Информирование пользователей с помощью информационной панели о временных изменениях в Microsoft OneNote, помогающих улучшить синхронизацию и доступность служб при высоком уровне использования по всему миру.</span><span class="sxs-lookup"><span data-stu-id="ed146-754">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="ed146-755">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-755">Project</span></span>

- <span data-ttu-id="ed146-756">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="ed146-756">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-25"></a><span data-ttu-id="ed146-758">Версия 2003: 25 марта</span><span class="sxs-lookup"><span data-stu-id="ed146-758">Version 2003: March 25</span></span>
<span data-ttu-id="ed146-759">*Версия 2003 (сборка 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="ed146-759">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-761">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-761">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-762">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-762">Excel</span></span>

- <span data-ttu-id="ed146-763">**Ваши любимые функции Excel теперь работают быстрее.** Функции СУММЕСЛИМН, СРЗНАЧЕСЛИМН, СЧЁТЕСЛИМН, МАКСЕСЛИМН и МИНЕСЛИМН теперь работают намного быстрее.</span><span class="sxs-lookup"><span data-stu-id="ed146-763">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="ed146-764">Быстрее переходите к итоговой строке.</span><span class="sxs-lookup"><span data-stu-id="ed146-764">Get to the bottom line more quickly.</span></span> <span data-ttu-id="ed146-765">Попробуйте уже сейчас.</span><span class="sxs-lookup"><span data-stu-id="ed146-765">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-766">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-766">Outlook</span></span>

- <span data-ttu-id="ed146-767">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="ed146-767">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="ed146-768">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="ed146-768">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="ed146-769">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="ed146-769">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="ed146-770">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="ed146-770">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="ed146-771">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-771">PowerPoint</span></span>

- <span data-ttu-id="ed146-772">**Комментарии.** Новые функций комментирования в PowerPoint позволяют быстро и легко находить и добавлять комментарии к документам.</span><span class="sxs-lookup"><span data-stu-id="ed146-772">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="ed146-773">Модернизируйте совместную работу с помощью новых функций, таких как привязка комментариев, сопоставление, задачи, улучшенные уведомления об упоминаниях и т. д.</span><span class="sxs-lookup"><span data-stu-id="ed146-773">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-774">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-774">Word</span></span>

- <span data-ttu-id="ed146-775">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="ed146-775">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ed146-776">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-776">Office Suite</span></span>

- <span data-ttu-id="ed146-777">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="ed146-777">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-780">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-780">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-781">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-781">Excel</span></span>

- <span data-ttu-id="ed146-782">В ряде случаев приложение Excel аварийно завершало работу при повторном открытии книги, внедренной в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-782">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="ed146-783">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="ed146-783">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="ed146-784">Устранена проблема с производительностью при создании диаграмм на основе шаблонов.</span><span class="sxs-lookup"><span data-stu-id="ed146-784">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="ed146-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="ed146-785">OneNote</span></span>

- <span data-ttu-id="ed146-786">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ.</span><span class="sxs-lookup"><span data-stu-id="ed146-786">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="ed146-787">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="ed146-787">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="ed146-788">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="ed146-788">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-789">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-789">Outlook</span></span>

- <span data-ttu-id="ed146-790">Устранена проблема, из-за которой пользователи могли видеть процесс Outlook, задерживающийся в диспетчере задач после выхода.</span><span class="sxs-lookup"><span data-stu-id="ed146-790">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-791">PowerPoint</span></span>

- <span data-ttu-id="ed146-792">Улучшен сценарий копирования-вставки. При копировании фигуры в слайде PowerPoint и вставке ее в другой слайд за один раз может произойти сбой с исключением.</span><span class="sxs-lookup"><span data-stu-id="ed146-792">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="ed146-793">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-793">Project</span></span>

- <span data-ttu-id="ed146-794">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="ed146-794">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="ed146-795">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="ed146-795">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="ed146-796">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="ed146-796">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="ed146-797">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="ed146-797">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-10"></a><span data-ttu-id="ed146-799">Версия 2002: 10 марта</span><span class="sxs-lookup"><span data-stu-id="ed146-799">Version 2002: March 10</span></span>
<span data-ttu-id="ed146-800">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="ed146-800">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="ed146-801">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-801">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-803">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-803">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="ed146-804">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-804">PowerPoint</span></span>

- <span data-ttu-id="ed146-805">**Ссылка на слайд:** попросите коллег поучаствовать в создании презентации и направьте их прямо на нужный слайд.</span><span class="sxs-lookup"><span data-stu-id="ed146-805">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-808">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-808">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="ed146-809">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-809">Project</span></span>

- <span data-ttu-id="ed146-810">Устранена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="ed146-810">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-01"></a><span data-ttu-id="ed146-812">Версия 2002: 1 марта</span><span class="sxs-lookup"><span data-stu-id="ed146-812">Version 2002: March 01</span></span>
<span data-ttu-id="ed146-813">*Версия 2002 (сборка 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="ed146-813">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-815">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-815">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ed146-816">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-816">Outlook</span></span>

- <span data-ttu-id="ed146-817">Исправлена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="ed146-817">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-25"></a><span data-ttu-id="ed146-819">Версия 2002: 25 февраля</span><span class="sxs-lookup"><span data-stu-id="ed146-819">Version 2002: February 25</span></span>
<span data-ttu-id="ed146-820">*Версия 2002 (сборка 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="ed146-820">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-822">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-822">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-823">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-823">Excel</span></span>

- <span data-ttu-id="ed146-824">**Статистика книги:** мы считаем ячейки, формулы, диаграммы и таблицы, чтобы вам не требовалось заниматься этим.</span><span class="sxs-lookup"><span data-stu-id="ed146-824">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="ed146-825">**Профилирование данных в редакторе запросов.** Получайте быстрый анализ данных в столбцах, выявляйте ошибки и пустые значения, просматривайте гистограммы распределения и т. д.</span><span class="sxs-lookup"><span data-stu-id="ed146-825">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-828">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-828">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-829">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-829">Excel</span></span>

- <span data-ttu-id="ed146-830">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="ed146-830">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-831">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-831">Outlook</span></span>

- <span data-ttu-id="ed146-832">Исправлена проблема, из-за которой запятые в поле месторасположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="ed146-832">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="ed146-833">Исправлена проблема, которая могла приводить к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="ed146-833">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="ed146-834">Устранена проблема, из-за которой параметр отключения выделения помеченных элементов не учитывался в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="ed146-834">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="ed146-835">Исправлена проблема, из-за которой приложение Outlook неожиданно синхронизировало всю почту, даже если ползунок синхронизации настроен на меньшее значение.</span><span class="sxs-lookup"><span data-stu-id="ed146-835">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="ed146-836">Устранена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке "От" отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="ed146-836">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="ed146-837">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span><span class="sxs-lookup"><span data-stu-id="ed146-837">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2001-february-19"></a><span data-ttu-id="ed146-839">Версия 2001: 19 февраля</span><span class="sxs-lookup"><span data-stu-id="ed146-839">Version 2001: February 19</span></span>
<span data-ttu-id="ed146-840">*Версия 2001 (сборка 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="ed146-840">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="ed146-841">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="ed146-841">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="ed146-842">Версия 2001: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="ed146-842">Version 2001: February 11</span></span>
<span data-ttu-id="ed146-843">*Версия 2001 (сборка 12430,20264)*</span><span class="sxs-lookup"><span data-stu-id="ed146-843">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="ed146-844">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-844">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-846">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-846">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-847">Access</span><span class="sxs-lookup"><span data-stu-id="ed146-847">Access</span></span>

- <span data-ttu-id="ed146-848">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="ed146-848">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="ed146-849">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="ed146-849">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="ed146-850">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-850">Excel</span></span>

- <span data-ttu-id="ed146-851">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="ed146-851">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="ed146-852">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="ed146-852">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-853">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-853">Outlook</span></span>

- <span data-ttu-id="ed146-854">Решает проблему, из-за которой у пользователей возникал сбой при указании неверного адреса От.</span><span class="sxs-lookup"><span data-stu-id="ed146-854">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="ed146-855">Решает проблему, которая приводила к сбою пользователей при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="ed146-855">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="ed146-856">Project</span><span class="sxs-lookup"><span data-stu-id="ed146-856">Project</span></span>

- <span data-ttu-id="ed146-857">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="ed146-857">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ed146-858">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-858">Office Suite</span></span>

- <span data-ttu-id="ed146-859">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="ed146-859">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2001-january-30"></a><span data-ttu-id="ed146-861">Версия 2001: 30 января</span><span class="sxs-lookup"><span data-stu-id="ed146-861">Version 2001: January 30</span></span>
<span data-ttu-id="ed146-862">*Версия 2001 (сборка 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="ed146-862">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-864">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-864">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-865">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-865">Excel</span></span>

- <span data-ttu-id="ed146-866">**Быстрое прочтение и ответ.** Отвечайте на примечания и упоминания прямо в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="ed146-866">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="ed146-867">**Посмотрите налево, посмотрите направо… ПРОСМОТРX уже доступен!:** построчно просмотрите и найдите нужные элементы в таблице или диапазоне с помощью функции ПРОМОТРX.</span><span class="sxs-lookup"><span data-stu-id="ed146-867">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="ed146-868">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-868">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="ed146-869">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-869">Outlook</span></span>

- <span data-ttu-id="ed146-870">**Дополнительные параметры электронной почты группы.** Эта функция позволяет группам пользователей настраивать сообщения или события, получаемые и отслеживаемые в папке "Входящие".</span><span class="sxs-lookup"><span data-stu-id="ed146-870">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="ed146-871">**Политика именования групп.** Политика именования групп позволяет ИТ-администратору стандартизировать имена групп, созданных пользователями в организации, а также управлять ими.</span><span class="sxs-lookup"><span data-stu-id="ed146-871">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="ed146-872">Администратор может требовать добавления специального префикса и суффикса к имени группы при ее создании и может запретить использование определенных слов.</span><span class="sxs-lookup"><span data-stu-id="ed146-872">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="ed146-873">Это позволяет уменьшить использование недопустимых слов в названиях групп, а также управлять отображением групп в каталоге.</span><span class="sxs-lookup"><span data-stu-id="ed146-873">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="ed146-874">Политика именования также помогает организациям развертывать сайты групп для их классификации по отделам.</span><span class="sxs-lookup"><span data-stu-id="ed146-874">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-875">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-875">Word</span></span>

- <span data-ttu-id="ed146-876">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="ed146-876">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="ed146-877">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-877">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="ed146-878">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="ed146-878">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="ed146-879">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="ed146-879">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="ed146-880">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-880">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-883">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-883">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-884">Access</span><span class="sxs-lookup"><span data-stu-id="ed146-884">Access</span></span>

- <span data-ttu-id="ed146-885">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="ed146-885">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="ed146-886">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="ed146-886">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="ed146-887">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="ed146-887">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="ed146-888">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-888">Excel</span></span>

- <span data-ttu-id="ed146-889">Исправлена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="ed146-889">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="ed146-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-890">Outlook</span></span>

- <span data-ttu-id="ed146-891">Исправлена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="ed146-891">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-january-22"></a><span data-ttu-id="ed146-893">Версия 1912: 22 января</span><span class="sxs-lookup"><span data-stu-id="ed146-893">Version 1912: January 22</span></span>
<span data-ttu-id="ed146-894">*Версия 1912 (сборка 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="ed146-894">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-896">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-896">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ed146-897">Доступ</span><span class="sxs-lookup"><span data-stu-id="ed146-897">Access</span></span>

- <span data-ttu-id="ed146-898">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="ed146-898">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-january-14"></a><span data-ttu-id="ed146-900">Версия 1912: 14 января</span><span class="sxs-lookup"><span data-stu-id="ed146-900">Version 1912: January 14</span></span>
<span data-ttu-id="ed146-901">*Версия 1912 (сборка 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="ed146-901">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="ed146-902">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ed146-902">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="ed146-903">Версия 1912: 8 января</span><span class="sxs-lookup"><span data-stu-id="ed146-903">Version 1912: January 08</span></span>
<span data-ttu-id="ed146-904">*Версия 1912 (сборка 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="ed146-904">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="ed146-906">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="ed146-906">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-907">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-907">Outlook</span></span>

- <span data-ttu-id="ed146-908">**Отправка писем со специальными возможностями пользователям, которым они нужны.** Outlook отображает подсказку, помогающую обеспечить доступность контента при отправке пользователю, который предпочитает контент с поддержкой специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="ed146-908">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ed146-909">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ed146-909">PowerPoint</span></span>

- <span data-ttu-id="ed146-910">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="ed146-910">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="ed146-911">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="ed146-911">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="ed146-912">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="ed146-912">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="ed146-913">Подробнее</span><span class="sxs-lookup"><span data-stu-id="ed146-913">Learn more</span></span>](https://support.office.com/ru-RU/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="ed146-916">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="ed146-916">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ed146-917">Excel</span><span class="sxs-lookup"><span data-stu-id="ed146-917">Excel</span></span>

- <span data-ttu-id="ed146-918">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="ed146-918">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="ed146-919">Outlook</span><span class="sxs-lookup"><span data-stu-id="ed146-919">Outlook</span></span>

- <span data-ttu-id="ed146-920">Исправлена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="ed146-920">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="ed146-921">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="ed146-921">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="ed146-922">Исправлена проблема, из-за которой пользователи иногда сталкивались с отправкой сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="ed146-922">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="ed146-923">Исправлена проблема, приводившая к зависаниям у пользователей в Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="ed146-923">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="ed146-924">Word</span><span class="sxs-lookup"><span data-stu-id="ed146-924">Word</span></span>

- <span data-ttu-id="ed146-925">Диспетчер стандартных блоков может отображать неправильное оповещение: "Были изменены стили, стандартные блоки".</span><span class="sxs-lookup"><span data-stu-id="ed146-925">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="ed146-926">Набор Office</span><span class="sxs-lookup"><span data-stu-id="ed146-926">Office Suite</span></span>

- <span data-ttu-id="ed146-927">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="ed146-927">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="ed146-929">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="ed146-929">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|CC|Production| |16.0.13328.20292|version-2010-october-27|)
[//]: # (|Win32|CC|Production| |16.0.13231.20418|version-2009-october-21|)
[//]: # (|Win32|CC|Production| |16.0.13231.20390|version-2009-october-13|)
[//]: # (|Win32|CC|Production| |16.0.13231.20368|version-2009-october-08|)
[//]: # (|Win32|CC|Production| |16.0.13231.20262|version-2009-september-28|)
[//]: # (|Win32|CC|Production| |16.0.13127.20508|version-2008-september-22|)
[//]: # (|Win32|CC|Production| |16.0.13127.20408|version-2008-september-09|)
[//]: # (|Win32|CC|Production| |16.0.13127.20296|version-2008-august-31|)
[//]: # (|Win32|CC|Production| |16.0.13029.20460|version-2007-august-25|)
[//]: # (|Win32|CC|Production| |16.0.13029.20344|version-2007-august-11|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
