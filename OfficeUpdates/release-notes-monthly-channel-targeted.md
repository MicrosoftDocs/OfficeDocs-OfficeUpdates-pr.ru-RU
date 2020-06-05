---
title: Заметки о выпуске для канала Monthly Channel (Targeted)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с поздним доступом последний список ключевых новых функций, исправлений или известных проблем
ms.openlocfilehash: 41dba1efa79735aafd74b318fd49c7c3211736e3
ms.sourcegitcommit: e9b127c7dfd80f3beb3c9aa9dadfb9e7f442c58c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563679"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="2dd39-103">Заметки о выпуске для канала Office Monthly Channel (Targeted)</span><span class="sxs-lookup"><span data-stu-id="2dd39-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="2dd39-104">Эта статья содержит заметки о выпуске для сборок Monthly Channel (Targeted) приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows.</span><span class="sxs-lookup"><span data-stu-id="2dd39-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="2dd39-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="2dd39-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="2dd39-106">Обратите внимание, что мы часто выпускаем функции (а иногда даже исправления) для Monthly Channel (Targeted) по истечении определенного времени.</span><span class="sxs-lookup"><span data-stu-id="2dd39-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="2dd39-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="2dd39-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="2dd39-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="2dd39-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="2dd39-109">Мы вносим некоторые изменения в каналы обновления для Приложений Microsoft 365, в том числе добавляем новый канал обновления (Monthly Enterprise Channel) и переименовываем существующие каналы обновления.</span><span class="sxs-lookup"><span data-stu-id="2dd39-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="2dd39-110">Дополнительные сведения см. в [этой статье](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="2dd39-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="2dd39-111">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки.</span><span class="sxs-lookup"><span data-stu-id="2dd39-111">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (НЕ УДАЛЯТЬ)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-june-04"></a><span data-ttu-id="2dd39-115">Версия 2005:4 июня</span><span class="sxs-lookup"><span data-stu-id="2dd39-115">Version 2005: June 04</span></span>
<span data-ttu-id="2dd39-116">*Версия 2005 (сборка 12827,20320)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-116">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-118">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-118">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2dd39-119">Access</span><span class="sxs-lookup"><span data-stu-id="2dd39-119">Access</span></span>

- <span data-ttu-id="2dd39-120">**Следите за временами! Расширенный тип данных Date/Time имеет лучшую точность.:** введение нового и усовершенствованного типа данных.</span><span class="sxs-lookup"><span data-stu-id="2dd39-120">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="2dd39-121">Для улучшения совместимости синтаксиса с SQL, а также для повышения точности и уровня детализации записей, включающих даты и время, мы реализуем тип данных DateTime2 в Access.</span><span class="sxs-lookup"><span data-stu-id="2dd39-121">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="2dd39-122">Эта дополнительная Дата & тип данных времени будет включать больший диапазон дат (от 0001-01-01 до 9999-12-31), с более высокой заданной точностью (наносекундах), а не с секундами, с помощью которой вы сможете предоставлять и выполнять вычисления.</span><span class="sxs-lookup"><span data-stu-id="2dd39-122">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="2dd39-123">Чтобы включить, выберите новое поле > Дата & время расширено.</span><span class="sxs-lookup"><span data-stu-id="2dd39-123">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="2dd39-124">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-124">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="2dd39-125">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-125">Excel</span></span>

- <span data-ttu-id="2dd39-126">**Создание сводных таблиц из наборов данных в Power BI в Excel:** Вы можете создавать сводные таблицы в Excel, которые подключены к наборам данных, хранящимся в Power BI, с несколькими щелчками мышью.</span><span class="sxs-lookup"><span data-stu-id="2dd39-126">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="2dd39-127">Это позволяет получить лучшие из сводных таблиц и Power BI.</span><span class="sxs-lookup"><span data-stu-id="2dd39-127"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="2dd39-128">Расчет, сведение и анализ данных со сводными таблицами из наборов данных безопасного Power BI.</span><span class="sxs-lookup"><span data-stu-id="2dd39-128">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-129">Outlook</span></span>

- <span data-ttu-id="2dd39-130">**Возможность быстрого повторного открытия элементов из предыдущего сеанса Outlook:** Мы добавили возможность быстрого повторного открытия элементов из предыдущего сеанса Outlook.</span><span class="sxs-lookup"><span data-stu-id="2dd39-130">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-133">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-133">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2dd39-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-134">PowerPoint</span></span>

- <span data-ttu-id="2dd39-135">Это приводит к устранению сбоя, если у пользователей есть как современные, так и устаревшие комментарии в файле, что приводит к обновлению комментариев.</span><span class="sxs-lookup"><span data-stu-id="2dd39-135">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2dd39-136">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-136">Office Suite</span></span>

- <span data-ttu-id="2dd39-137">Мы разрешали проблему с частотой сбоев Валидатеинсталл, установив для проверки надстройки Bing надстройку значение true по умолчанию и учитывая успешный возврат MSI в качестве успешной установки.</span><span class="sxs-lookup"><span data-stu-id="2dd39-137">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-29"></a><span data-ttu-id="2dd39-139">Версия 2005:29 мая</span><span class="sxs-lookup"><span data-stu-id="2dd39-139">Version 2005: May 29</span></span>
<span data-ttu-id="2dd39-140">*Версия 2005 (сборка 12827,20268)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-140">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-142">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-142">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="2dd39-143">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-143">Excel</span></span>

- <span data-ttu-id="2dd39-144">**Представление листа:** Сортировка и фильтрация при совместной работе с другими пользователями в классической версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2dd39-144">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-145">Outlook</span></span>

- <span data-ttu-id="2dd39-146">**Дополнительные кнопки, добавленные в всплывающие уведомления Outlook:** Кнопки быстрого действия теперь отображаются в всплывающих уведомлениях Outlook при запуске Outlook в Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2dd39-146">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-149">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-149">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="2dd39-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-150">Outlook</span></span>

- <span data-ttu-id="2dd39-151">Исправлена ошибка, из – за которой пользователи версий Windows 10 Server выводят предупреждение о состоянии "предупреждение": недопустимый.</span><span class="sxs-lookup"><span data-stu-id="2dd39-151">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="2dd39-152">Эта версия Windows поддерживает обнаружение вирусов, но антивирусное по не обнаружено, несмотря на то, что антивирусная программа установлена правильно.</span><span class="sxs-lookup"><span data-stu-id="2dd39-152">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2dd39-153">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-153">Office Suite</span></span>

- <span data-ttu-id="2dd39-154">Сбой ведущего приложения Office в Windows при активации надстройки, когда раздел реестра HKEY_CURRENT_USER \Софтваре\микрософт\интернет Експлорер\маин\табпрокгровс имеет значение 0.</span><span class="sxs-lookup"><span data-stu-id="2dd39-154">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2dd39-155">Это изменение решает эту проблему.</span><span class="sxs-lookup"><span data-stu-id="2dd39-155">This change would fix this issue.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-21"></a><span data-ttu-id="2dd39-157">Версия 2005:21 мая</span><span class="sxs-lookup"><span data-stu-id="2dd39-157">Version 2005: May 21</span></span>
<span data-ttu-id="2dd39-158">*Версия 2005 (сборка 12827,20210)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-158">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-160">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-160">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-161">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-161">Excel</span></span>

- <span data-ttu-id="2dd39-162">**Получение данных Организации из Power BI с использованием типов данных Excel:** Вы можете вставлять данные из вашей организации с помощью типов данных Excel.</span><span class="sxs-lookup"><span data-stu-id="2dd39-162">**Get Organization Data from Power BI using Excel Data Types:** You can insert data from your Organization using Excel Data Types.</span></span> <span data-ttu-id="2dd39-163">Преобразуйте ячейку в книге и получите дополнительные сведения, а затем обновите данные в любое время.</span><span class="sxs-lookup"><span data-stu-id="2dd39-163">Convert a cell in your workbook and get additional information, and refresh the data anytime you need!</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-166">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-167">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-167">Excel</span></span>

- <span data-ttu-id="2dd39-168">Исправлена ошибка, из-за которой Excel может перестать отвечать после использования сочетания клавиш CTRL + SHIFT + клавиша со стрелками для прокрутки окна Excel, доступ к которому предоставлен в Teams.</span><span class="sxs-lookup"><span data-stu-id="2dd39-168">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="2dd39-169">В некоторых случаях щелчок гиперссылки на место в той же книге приведет к скрытию книги.</span><span class="sxs-lookup"><span data-stu-id="2dd39-169">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="2dd39-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-170">Outlook</span></span>

- <span data-ttu-id="2dd39-171">Устранена ошибка, связанная с событием CLP для метки "ответить" и "Переслать".</span><span class="sxs-lookup"><span data-stu-id="2dd39-171">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="2dd39-172">Устранена ошибка, из — за которой пользователи могут столкнуться со сбоем при отправке отзыва из уведомления администратора.</span><span class="sxs-lookup"><span data-stu-id="2dd39-172">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2005-may-14"></a><span data-ttu-id="2dd39-174">Версия 2005:14 мая</span><span class="sxs-lookup"><span data-stu-id="2dd39-174">Version 2005: May 14</span></span>
<span data-ttu-id="2dd39-175">*Версия 2005 (сборка 12827,20160)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-175">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-177">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-177">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-178">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-178">Excel</span></span>

- <span data-ttu-id="2dd39-179">**Автоматически применять или рекомендовать метки конфиденциальности:** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального контента.</span><span class="sxs-lookup"><span data-stu-id="2dd39-179">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-180">PowerPoint</span></span>

- <span data-ttu-id="2dd39-181">**Отсутствие необходимости для щелчка: вы еарбудс:** Используйте Еарбудс поверхности для управления презентациями PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2dd39-181">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="2dd39-182">Важно! чтобы использовать жесты для управления презентациями, необходимо связать Еарбудс поверхности в приложении Surface Audio для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="2dd39-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="2dd39-183">Инструкции по началу работы с приложением Surface Audio в Windows 10 доступны здесь.</span><span class="sxs-lookup"><span data-stu-id="2dd39-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="2dd39-184">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="2dd39-185">**Автоматически применять или рекомендовать метки конфиденциальности:** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального контента.</span><span class="sxs-lookup"><span data-stu-id="2dd39-185">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-186">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-186">Word</span></span>

- <span data-ttu-id="2dd39-187">**Автоматически применять или рекомендовать метки конфиденциальности:** Office может рекомендовать или автоматически применять метку конфиденциальности на основе обнаруженного конфиденциального контента.</span><span class="sxs-lookup"><span data-stu-id="2dd39-187">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-190">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-190">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2dd39-191">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-191">Excel</span></span>

- <span data-ttu-id="2dd39-192">Увеличен размер элементов управления ссылкой на ячейку в диалоговом окне «Пользовательские панели ошибок», используемом с диаграммами.</span><span class="sxs-lookup"><span data-stu-id="2dd39-192">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="2dd39-193">Исправлена проблема, из-за которой в таблице данных диаграммы неправильно отображались значения оси дат.</span><span class="sxs-lookup"><span data-stu-id="2dd39-193">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="2dd39-194">Исправлена проблема, из-за которой разрывы страниц не удавалось отключить после перехода в режим макета страницы или страничный режим.</span><span class="sxs-lookup"><span data-stu-id="2dd39-194">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="2dd39-195">Исправлена проблема, из-за которой стили линий диаграммы могли пропадать после скрытия и повторного отображения столбцов с рядами данных.</span><span class="sxs-lookup"><span data-stu-id="2dd39-195">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="2dd39-196">Исправлена ошибка, в результате которой при вставке столбца в отфильтрованном списке потребуется больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="2dd39-196">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2dd39-197">Исправлена проблема с масштабированием флажков в элементах управления формы при печати.</span><span class="sxs-lookup"><span data-stu-id="2dd39-197">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2dd39-198">Исправлена ошибка, из-за которой внешняя ссылка перестает работать после повторного открытия файла, если путь к файлу слишком длинный.</span><span class="sxs-lookup"><span data-stu-id="2dd39-198">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2dd39-199">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2dd39-199">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2dd39-200">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="2dd39-200">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2dd39-201">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2dd39-201">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2dd39-202">Это изменение устраняет проблему, из-за которой информация об условном форматировании (CF) неправильно сохранялась в файлы XLSB.</span><span class="sxs-lookup"><span data-stu-id="2dd39-202">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="2dd39-203">Это изменение устраняет проблему, из-за которой величина достоверности аппроксимации линии тренда на диаграмме (в случае вынужденного пересечения с осью Y) была неверной, несмотря на то, что функция ЛИНЕЙН возвращает правильное значение.</span><span class="sxs-lookup"><span data-stu-id="2dd39-203">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="2dd39-204">Это изменение устраняет проблему, из-за которой настроенное форматирование линии тренда на диаграмме не всегда сохранялось.</span><span class="sxs-lookup"><span data-stu-id="2dd39-204">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="2dd39-205">При попытке перечислить изменения на новом листе книги, использующей устаревший режим "Общая книга", может произойти сбой.</span><span class="sxs-lookup"><span data-stu-id="2dd39-205">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="2dd39-206">Исправлена проблема, из-за которой пользовательское форматирование в сводных диаграммах не сохранялось при включенном параметре "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="2dd39-206">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="2dd39-207">Исправлена проблема, из-за которой пользовательское форматирование одной точки данных в сводной диаграмме не сохранялось, если был выбран параметр "Инверсия для чисел <0".</span><span class="sxs-lookup"><span data-stu-id="2dd39-207">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="2dd39-208">Это исправление устраняет проблему, из-за которой символ "@", отправленный в CSV-файл, приводил к преобразованию строки после символа "@" в формулу.</span><span class="sxs-lookup"><span data-stu-id="2dd39-208">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="2dd39-209">Исправлена проблема, из-за которой десятичные значения в функции ПОСЛЕДОВ округлялись неправильно.</span><span class="sxs-lookup"><span data-stu-id="2dd39-209">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="2dd39-210">OneNote</span><span class="sxs-lookup"><span data-stu-id="2dd39-210">OneNote</span></span>

- <span data-ttu-id="2dd39-211">Исправлена ошибка, из-за которой разрывы строк сохранялись в виде вертикальных вкладок.</span><span class="sxs-lookup"><span data-stu-id="2dd39-211">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-212">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-212">Outlook</span></span>

- <span data-ttu-id="2dd39-213">Решает проблему, из-за которой пользователи не могли добавить личную группу контактов в качестве участника собрания.</span><span class="sxs-lookup"><span data-stu-id="2dd39-213">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="2dd39-214">Исправлена ошибка, из – за которой в ленте Office отключена кнопка категории для календарей группировки.</span><span class="sxs-lookup"><span data-stu-id="2dd39-214">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="2dd39-215">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="2dd39-215">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="2dd39-216">Устранена проблема с группой папок корпоративных клиентов, которые не были реализованы или не работали, из-за чего в Outlook отображалось сообщение "Не отвечает".</span><span class="sxs-lookup"><span data-stu-id="2dd39-216">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="2dd39-217">Устранена ошибка, из-за которой при отправке на клиенте Outlook для настольных компьютеров была нажата очень длинная сафелинкс.</span><span class="sxs-lookup"><span data-stu-id="2dd39-217">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="2dd39-218">Исправлена проблема, из-за которой папки Outlook с именами, содержащими двухбайтовые знаки (DBCS), периодически исчезали при синхронизации с сервером.</span><span class="sxs-lookup"><span data-stu-id="2dd39-218">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="2dd39-219">Чтобы это происходило, Outlook должен быть настроен с использованием учетной записи IMAP и работать в системе, языком которой выбран японский.</span><span class="sxs-lookup"><span data-stu-id="2dd39-219">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="2dd39-220">Исправлена ошибка, из – за которой правила, созданные для почтовых ящиков, отличных от основного почтового ящика пользователя, станут недействительными.</span><span class="sxs-lookup"><span data-stu-id="2dd39-220">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="2dd39-221">Устранена ошибка, из – за которой вложения отправляются при пересылке зашифрованного сообщения.</span><span class="sxs-lookup"><span data-stu-id="2dd39-221">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="2dd39-222">Устранена ошибка, из — за которой не удается отобразить тему собрания в помощнике по планированию собраний с более чем 2 месяцами.</span><span class="sxs-lookup"><span data-stu-id="2dd39-222">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="2dd39-223">Устранена проблема, из-за которой пользователи видели усечение тела сообщения при пересылке больших сообщений HTML.</span><span class="sxs-lookup"><span data-stu-id="2dd39-223">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2dd39-224">Добавлена возможность применять стандартную настройку подписи S/MIME с помощью групповой политики.</span><span class="sxs-lookup"><span data-stu-id="2dd39-224">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-225">PowerPoint</span></span>

- <span data-ttu-id="2dd39-226">Исправлена следующая проблема: если пользователь создавал комментарий, не публикуя его, и закрывал область комментариев, затем открывал новое окно, просматривал несколько слайдов, закрывал окно и повторно открывал область комментариев в исходной презентации, черновик комментария был недоступен.</span><span class="sxs-lookup"><span data-stu-id="2dd39-226">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="2dd39-227">Устранена проблема, из-за которой при наведении указателя на звездочку (\*) не отображалось имя пользователя и дата последнего обновления документа.</span><span class="sxs-lookup"><span data-stu-id="2dd39-227">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="2dd39-228">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-228">Project</span></span>

- <span data-ttu-id="2dd39-229">Когда данные Предшественника / Преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="2dd39-229">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="2dd39-230">Исправлена ошибка, из-за которой Project мог аварийно завершить работу при изменении поля состояния платы в проекте, подключенном к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2dd39-230">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="2dd39-231">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="2dd39-231">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2dd39-232">Исправлена ошибка, из-за которой если приложение Project подключено к Project Web App, а разделитель целой и дробной части является запятыми, метод TaskDependencies Add завершается с ошибкой при добавлении запаздывания.</span><span class="sxs-lookup"><span data-stu-id="2dd39-232">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="2dd39-233">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-233">Word</span></span>

- <span data-ttu-id="2dd39-234">Исправлена проблема, из-за которой иногда не удавалось вставить комментарии в документ в режиме совместной работы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-234">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="2dd39-235">Это изменение исправляет ошибку, из-за которой карточка "Люди" мерцала при щелчке по @упоминанию.</span><span class="sxs-lookup"><span data-stu-id="2dd39-235">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="2dd39-236">При включении параметра "Показывать закладки" закладки не отображались.</span><span class="sxs-lookup"><span data-stu-id="2dd39-236">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="2dd39-237">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="2dd39-237">This has been fixed.</span></span>

- <span data-ttu-id="2dd39-238">Исправлена следующая проблема: пользователю, закрывавшему документ с черновиком комментариев, предлагалось подтвердить закрытие без сохранения черновика комментариев,</span><span class="sxs-lookup"><span data-stu-id="2dd39-238">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="2dd39-239">и при отмене запроса документ закрывался, а не оставался открытым.</span><span class="sxs-lookup"><span data-stu-id="2dd39-239">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="2dd39-240">Исправлена ошибка при копировании и вставке заголовков.</span><span class="sxs-lookup"><span data-stu-id="2dd39-240">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="2dd39-241">Исправлена ошибка, в результате которой при преобразовании опубликованного комментария возникнет ошибка "не удалось вставить переведенный текст".</span><span class="sxs-lookup"><span data-stu-id="2dd39-241">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="2dd39-242">Это исправление устраняет проблему, в результате которой текст с гиперссылками может не отображаться, если выбран параметр "отображать коды полей, а не их значения".</span><span class="sxs-lookup"><span data-stu-id="2dd39-242">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="2dd39-243">В веб-представлении или иммерсивном средстве чтения щелчок по подсказке приводил к прокручиванию в верхнюю часть представления, хотя она уже была просмотрена.</span><span class="sxs-lookup"><span data-stu-id="2dd39-243">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="2dd39-244">Эта ошибка исправлена.</span><span class="sxs-lookup"><span data-stu-id="2dd39-244">This has been fixed.</span></span>

- <span data-ttu-id="2dd39-245">Исправлена проблема, из-за которой попытка сохранения файла, содержащего макрос, под новым именем приводила к его сохранению с расширением DOCX и именем файла WRO0004.docx независимо от варианта, указанного пользователем. В результате появлялась ошибка о невозможности использования документа.</span><span class="sxs-lookup"><span data-stu-id="2dd39-245">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2dd39-246">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-246">Office Suite</span></span>

- <span data-ttu-id="2dd39-247">Когда пользователю назначается политика, которая перемещает их только в Teams, они по-прежнему могут использовать надстройку Outlook Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="2dd39-247">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="2dd39-248">После выполнения этого обновления вы больше не сможете планировать собрания Skype для бизнеса после того, как клиент прочитает политику, указывающую, что пользователь является только Teams, и переходит в режим только присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="2dd39-248">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="2dd39-249">Кроме того, надстройка Outlook для Skype для бизнеса не активируется при запуске, если он видит, что клиент Skype для бизнеса работает в режиме только присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="2dd39-249">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="2dd39-250">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="2dd39-250">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2dd39-251">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="2dd39-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-11"></a><span data-ttu-id="2dd39-253">Версия 2004: 11 мая</span><span class="sxs-lookup"><span data-stu-id="2dd39-253">Version 2004: May 11</span></span>
<span data-ttu-id="2dd39-254">*Версия 2004 (сборка 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-254">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-256">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-257">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-257">Excel</span></span>

- <span data-ttu-id="2dd39-258">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="2dd39-258">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-259">Outlook</span></span>

- <span data-ttu-id="2dd39-260">**Улучшенные ссылки в письмах:** если добавляется ссылка на файл, URL-адрес заменяется именем файла.</span><span class="sxs-lookup"><span data-stu-id="2dd39-260">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="2dd39-261">Вы можете изменить разрешения, чтобы доступ был у всех получателей.</span><span class="sxs-lookup"><span data-stu-id="2dd39-261">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="2dd39-262">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-262">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="2dd39-263">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="2dd39-263">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="2dd39-264">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="2dd39-264">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-265">PowerPoint</span></span>

- <span data-ttu-id="2dd39-266">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="2dd39-266">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="2dd39-267">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-267">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="2dd39-268">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-268">Word</span></span>

- <span data-ttu-id="2dd39-269">**Делайте доклады с помощью анимационных GIF**. Анимационные GIF теперь поддерживаются в редакторе Office — ваши документы стали еще более впечатляющими.</span><span class="sxs-lookup"><span data-stu-id="2dd39-269">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-272">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-272">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-273">Outlook</span></span>

- <span data-ttu-id="2dd39-274">Устранена проблема, из-за которой у пользователей возникали сбои при отображении всплывающих уведомлений.</span><span class="sxs-lookup"><span data-stu-id="2dd39-274">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-may-04"></a><span data-ttu-id="2dd39-276">Версия 2004: 04 мая</span><span class="sxs-lookup"><span data-stu-id="2dd39-276">Version 2004: May 04</span></span>
<span data-ttu-id="2dd39-277">*Версия 2004 (сборка 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-277">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-279">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-279">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-280">Outlook</span></span>

- <span data-ttu-id="2dd39-281">\*\*Лучшие результаты - в одно мгновение: \*\*мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="2dd39-281">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="2dd39-282">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-282">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="2dd39-283">**Уведомления об инцидентах для ИТ-администраторов.** Глобальные администраторы клиентов Microsoft 365 и администраторы приложений Office будут уведомляться об инцидентах Outlook и Office 365 Exchange, влияющих на пользователей, в новой правой боковой панели в Outlook для Windows.</span><span class="sxs-lookup"><span data-stu-id="2dd39-283">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-286">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-286">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2dd39-287">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-287">Office Suite</span></span>

- <span data-ttu-id="2dd39-288">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="2dd39-288">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-29"></a><span data-ttu-id="2dd39-290">Версия 2004: 29 апреля</span><span class="sxs-lookup"><span data-stu-id="2dd39-290">Version 2004: April 29</span></span>
<span data-ttu-id="2dd39-291">*Версия 2004 (сборка 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-291">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-293">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-293">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-294">Outlook</span></span>

- <span data-ttu-id="2dd39-295">**Помощь в защите данных в группе.** Метка конфиденциальности, которую можно выбрать при создании группы, применяется к сообщениям электронной почты, документам и командным сайтам группы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-295">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-298">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-298">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-299">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-299">Outlook</span></span>

- <span data-ttu-id="2dd39-300">Исправлена проблема, приводившая к сбою Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="2dd39-300">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-25"></a><span data-ttu-id="2dd39-302">Версия 2004: 25 апреля</span><span class="sxs-lookup"><span data-stu-id="2dd39-302">Version 2004: April 25</span></span>
<span data-ttu-id="2dd39-303">*Версия 2004 (сборка 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-303">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-305">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-305">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-306">Outlook</span></span>

- <span data-ttu-id="2dd39-307">Исправлена проблема, приводившая к сбою Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="2dd39-307">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="2dd39-308">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-308">Project</span></span>

- <span data-ttu-id="2dd39-309">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="2dd39-309">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2dd39-310">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-310">Office Suite</span></span>

- <span data-ttu-id="2dd39-311">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="2dd39-311">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-21"></a><span data-ttu-id="2dd39-313">Версия 2004: 21 апреля</span><span class="sxs-lookup"><span data-stu-id="2dd39-313">Version 2004: April 21</span></span>
<span data-ttu-id="2dd39-314">*Версия 2004 (сборка 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-314">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-316">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-316">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-317">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-317">Outlook</span></span>

- <span data-ttu-id="2dd39-318">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="2dd39-318">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2dd39-319">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="2dd39-319">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2004-april-15"></a><span data-ttu-id="2dd39-321">Версия 2004: 15 апреля</span><span class="sxs-lookup"><span data-stu-id="2dd39-321">Version 2004: April 15</span></span>
<span data-ttu-id="2dd39-322">*Версия 2004 (сборка 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-322">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-324">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-325">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-325">Excel</span></span>

- <span data-ttu-id="2dd39-326">**Поддержка коннектора Facebook заканчивается:** Начиная с апреля 2020 года Excel больше не будет поддерживать подключения к внешним данным, которые используют коннектор Facebook.</span><span class="sxs-lookup"><span data-stu-id="2dd39-326">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-327">Outlook</span></span>

- <span data-ttu-id="2dd39-328">**Новая опция, позволяющая отключить предложения @ упоминания при составлении писем в Outlook:** Считаете ли вы средство @ упоминания более раздражающим, чем полезным?</span><span class="sxs-lookup"><span data-stu-id="2dd39-328">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="2dd39-329">Теперь вы можете отключить его, если хотите.</span><span class="sxs-lookup"><span data-stu-id="2dd39-329">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-330">PowerPoint</span></span>

- <span data-ttu-id="2dd39-331">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="2dd39-331">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-332">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-332">Word</span></span>

- <span data-ttu-id="2dd39-333">**Аннотируйте вашу личную копию:** Создавайте рукописные заметки для ваших глаз, создавая личную копию общего документа.</span><span class="sxs-lookup"><span data-stu-id="2dd39-333">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="2dd39-334">Чтобы приступить к работе, перейдите в раздел Просмотр > Создать частную копию.</span><span class="sxs-lookup"><span data-stu-id="2dd39-334">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-337">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2dd39-338">Access</span><span class="sxs-lookup"><span data-stu-id="2dd39-338">Access</span></span>

- <span data-ttu-id="2dd39-339">Исправлены проблемы с изменением размера и обновлением таблиц на панели задач.</span><span class="sxs-lookup"><span data-stu-id="2dd39-339">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="2dd39-340">Исправлена проблема, из-за которой в международных версиях Access пользовательский интерфейс содержал строки на английском языке.</span><span class="sxs-lookup"><span data-stu-id="2dd39-340">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="2dd39-341">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-341">Excel</span></span>

- <span data-ttu-id="2dd39-342">Исправлена ошибка, из-за которой выбор диапазона ячеек на листе приводил к выбору одной ячейки.</span><span class="sxs-lookup"><span data-stu-id="2dd39-342">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="2dd39-343">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="2dd39-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2dd39-344">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="2dd39-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2dd39-345">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="2dd39-345">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2dd39-346">Исправлена проблема производительности, с которой могли сталкиваться пользователи при программном изменении большого диапазона ячеек.</span><span class="sxs-lookup"><span data-stu-id="2dd39-346">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="2dd39-347">Исправлена проблема производительности, возникавшая при открытии CSV-файлов в средах на японском языке.</span><span class="sxs-lookup"><span data-stu-id="2dd39-347">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="2dd39-348">Исправлена ошибка, из-за которой при вставке определенного пользователем шаблона диаграммы по умолчанию его сохраняли в виде столбчатой диаграммы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-348">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="2dd39-349">Исправлена ошибка, из-за которой метки данных на диаграммах отображались как пустые, если в базовых ячейках данных не было заголовка.</span><span class="sxs-lookup"><span data-stu-id="2dd39-349">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="2dd39-350">Исправлена проблема, из-за которой Excel мог перестать отвечать при уменьшении размера диаграммы с некоторыми диапазонами оси X.</span><span class="sxs-lookup"><span data-stu-id="2dd39-350">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="2dd39-351">Исправлена ошибка, из-за которой лист Excel с включенной ссылкой на ячейку R1C1, находящийся в соавторстве / совместном использовании, при наведении курсора на значок присутствия пользователя, не отображал ссылку активной ячейки в режиме R1C1.</span><span class="sxs-lookup"><span data-stu-id="2dd39-351">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="2dd39-352">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="2dd39-352">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-353">Outlook</span></span>

- <span data-ttu-id="2dd39-354">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="2dd39-354">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="2dd39-355">Благодаря этому изменению исправлена проблема, из-за которой не происходило обновление с сохранением последних изменений в черновиках сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2dd39-355">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="2dd39-356">Исправлена проблема, из-за которой было невозможно щелкнуть файл правой кнопкой мыши и использовать команду "Отправить".</span><span class="sxs-lookup"><span data-stu-id="2dd39-356">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="2dd39-357">Устранена проблема, из-за которой делегаты видели разные иерархии папок на разных компьютерах для общих почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="2dd39-357">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="2dd39-358">Устранена проблема, из-за которой категории иногда исчезали из сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="2dd39-358">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="2dd39-359">Устранена проблема, из-за которой некоторые напоминания не срабатывали при смене часового пояса на машине.</span><span class="sxs-lookup"><span data-stu-id="2dd39-359">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="2dd39-360">Устранена проблема, из-за которой у пользователей возникал сбой при попытке просмотра свойств организационной формы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-360">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="2dd39-361">Исправлена проблема, из-за которой при настроенном пользователем пути поиска для адресной книги область определения по именам в Outlook была ограничена настроенным путем, а не включала глобальный список адресов (AL).</span><span class="sxs-lookup"><span data-stu-id="2dd39-361">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="2dd39-362">Устранена проблема, из-за которой кнопка «Сохранить в облаке» отсутствовала в инструментах вложений.</span><span class="sxs-lookup"><span data-stu-id="2dd39-362">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2dd39-363">Устранена проблема, из-за которой пользователи не могли добавлять подпись при ответе на сообщение с цифровыми правами из окна инспектора, когда у пользователя нет разрешения Владельца на сообщение, на которое он отвечает.</span><span class="sxs-lookup"><span data-stu-id="2dd39-363">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="2dd39-364">Устранена проблема, из-за которой пользователи не могли добавлять дополнительные вложения из веб-сайта в ранее созданное собрание.</span><span class="sxs-lookup"><span data-stu-id="2dd39-364">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="2dd39-365">Устранена проблема, из-за которой дата «последнего изменения» в файле обновлялась при добавлении вложения в сообщение или при сохранении вложения из сообщения путем его перетаскивания (в отличие от меню).</span><span class="sxs-lookup"><span data-stu-id="2dd39-365">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="2dd39-366">Устранена проблема, из-за которой при вводе в расширенной области поиска не удавалось запустить поиск, вместо этого требовалось, чтобы пользователи нажимали кнопку поиска.</span><span class="sxs-lookup"><span data-stu-id="2dd39-366">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="2dd39-367">Исправлена проблема, из-за которой в наборе полученных результатов поиска при сортировке результатов по категориям не отображались цвета категорий.</span><span class="sxs-lookup"><span data-stu-id="2dd39-367">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="2dd39-368">Исправлена проблема, из-за которой в результатах поиска не отображаются сведения о пользователях, если отключен параметр "Показывать фотографии пользователей при наличии".</span><span class="sxs-lookup"><span data-stu-id="2dd39-368">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2dd39-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-369">PowerPoint</span></span>

- <span data-ttu-id="2dd39-370">Это изменение исправляет ошибку, которая могла возникать при сохранении файлов PowerPoint, содержащих эмодзи.</span><span class="sxs-lookup"><span data-stu-id="2dd39-370">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="2dd39-371">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-371">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="2dd39-372">Мы исправили проблему, когда копирование текста из Excel в PowerPoint могло изменить его форматирование.</span><span class="sxs-lookup"><span data-stu-id="2dd39-372">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="2dd39-373">Это изменение устраняет проблему, из-за которой поиск специальных символов с использованием «только поиск целых слов» не всегда работал должным образом.</span><span class="sxs-lookup"><span data-stu-id="2dd39-373">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="2dd39-374">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-374">Project</span></span>

- <span data-ttu-id="2dd39-375">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="2dd39-375">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2dd39-376">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="2dd39-376">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2dd39-377">Исправлена ошибка, из-за которой событие Visual Basic Applications (VBA) ProjectBeforeTaskChange не срабатывало, когда пользователь нажимал кнопку «Деактивировать», найденную на ленте задач в группе планирования.</span><span class="sxs-lookup"><span data-stu-id="2dd39-377">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="2dd39-378">При указании данных о предшествовавших или последующих задачах из представления Типа формы внесение изменений для события 'ProjectBeforeTaskChange' в приложениях Visual Basic (VBA) происходило не всегда.</span><span class="sxs-lookup"><span data-stu-id="2dd39-378">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="2dd39-379">Например, при удалении зависимости и нажатии "OK" в форме событие не срабатывало.</span><span class="sxs-lookup"><span data-stu-id="2dd39-379">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="2dd39-380">Это поведение исправлено.</span><span class="sxs-lookup"><span data-stu-id="2dd39-380">This behavior has been fixed.</span></span>

- <span data-ttu-id="2dd39-381">Исправлена проблема, из-за которой после внесения изменения, например, изменения даты, не отображались последние значения в поле фактической стоимости выполненных работ (ФСВР).</span><span class="sxs-lookup"><span data-stu-id="2dd39-381">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="2dd39-382">Исправлена проблема, из-за которой при открытии проекта через меню недавно использованных проектов файл проекта открывался с доступом для чтения и записи.</span><span class="sxs-lookup"><span data-stu-id="2dd39-382">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="2dd39-383">Благодаря этому изменению исправлена проблема, из-за которой при создании задачи вручную с датой начала и указанием времени (но без указания длительности), время для этой задачи на временной шкале отображалось неправильно.</span><span class="sxs-lookup"><span data-stu-id="2dd39-383">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="2dd39-384">Исправлена ошибка, из-за которой при печати временной шкалы с использованием календаря хиджры месяц пропускался или дублировался в представлении печати.</span><span class="sxs-lookup"><span data-stu-id="2dd39-384">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="2dd39-385">Это изменение направлено на исправление проблемы, из-за которой работа с объектами GDI в Планировщике работы группы могла привести к избыточному распределению объектов GDI и нехватке памяти.</span><span class="sxs-lookup"><span data-stu-id="2dd39-385">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="2dd39-386">Исправлена ошибка, из-за которой, если выполняется CustomFieldValueListGetItem 'и таблица поиска для настраиваемого поля не существует, создается пустая таблица поиска, хотя это не должно быть.</span><span class="sxs-lookup"><span data-stu-id="2dd39-386">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="2dd39-387">Когда данные редактора или преемника редактируются в представлении формы, запускается дополнительное событие ProjectBeforeTaskChange</span><span class="sxs-lookup"><span data-stu-id="2dd39-387">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="2dd39-388">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="2dd39-388">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-389">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-389">Word</span></span>

- <span data-ttu-id="2dd39-390">Это изменение устраняет проблему, из-за которой при наведении курсора на подсказку его карточка не выделялась.</span><span class="sxs-lookup"><span data-stu-id="2dd39-390">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="2dd39-391">Это изменение устраняет проблему, из-за которой на нескольких страницах в меню "Представление" область "Примечания" могла отображаться пустой.</span><span class="sxs-lookup"><span data-stu-id="2dd39-391">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="2dd39-392">Исправлена проблема, из-за которой были отключены функции размещения комментариев.</span><span class="sxs-lookup"><span data-stu-id="2dd39-392">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="2dd39-393">Это изменение устраняет проблему, из-за которой текст в сгруппированных фигурах временно исчезал при использовании инструмента выделения «Лассо».</span><span class="sxs-lookup"><span data-stu-id="2dd39-393">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="2dd39-394">Это изменение направлено на предотвращение задержек при обработке изображений с неверно сформированными или недействительными данными о протоколе.</span><span class="sxs-lookup"><span data-stu-id="2dd39-394">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="2dd39-395">Это изменение устраняет проблему, из-за которой рендеринг устаревшей диаграммы Excel, встроенной как объект OLE в PowerPoint или Word, не всегда отображал заголовок диаграммы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-395">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="2dd39-396">Это изменение направлено на исправление проблемы, при которой отправка сообщений диспетчера учетных записей не производилась, что приводило к зависанию сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="2dd39-396">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="2dd39-397">Это изменение устраняет проблему в двухстраничном представлении, при создании комментария привязка комментария не всегда появлялась.</span><span class="sxs-lookup"><span data-stu-id="2dd39-397">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="2dd39-398">Исправлена проблема, из-за которой при вводе или изменении примечания и использовании клавиш CTRL+A происходило выделение текста на холсте, вместо выделения текста только в карточке примечания.</span><span class="sxs-lookup"><span data-stu-id="2dd39-398">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="2dd39-399">Исправлена ошибка, из-за которой, если абзац, стиль которого является предком стиля, связанного со списком, нумерация этого списка может быть потеряна.</span><span class="sxs-lookup"><span data-stu-id="2dd39-399">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="2dd39-400">Благодаря этому изменению исправлена проблема, из-за которой в Оглавлении обновлялись стили заголовков, которые отсутствовали в документе.</span><span class="sxs-lookup"><span data-stu-id="2dd39-400">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="2dd39-401">Мы исправили проблему, из-за которой выравнивание слова в документе зашифровывается при попытке изменить его после печати с использованием Quick Print.</span><span class="sxs-lookup"><span data-stu-id="2dd39-401">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="2dd39-402">Мы исправили проблему при объединении двух документов в один.</span><span class="sxs-lookup"><span data-stu-id="2dd39-402">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2dd39-403">Исправлена проблема, из-за которой удалялись сохраненные в документах Word электронные подписи при отправке документов по почте.</span><span class="sxs-lookup"><span data-stu-id="2dd39-403">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="2dd39-404">Исправлена проблема, из-за которой пометка исправлений, связанных с формулами, могла привести к сбою при сохранении файла.</span><span class="sxs-lookup"><span data-stu-id="2dd39-404">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-14"></a><span data-ttu-id="2dd39-406">Версия 2003: 14 апреля</span><span class="sxs-lookup"><span data-stu-id="2dd39-406">Version 2003: April 14</span></span>
<span data-ttu-id="2dd39-407">*Версия 2003 (сборка 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-407">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="2dd39-408">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2dd39-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

- <span data-ttu-id="2dd39-410">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2dd39-410">Various bugs and performance fixes.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-09"></a><span data-ttu-id="2dd39-412">Версия 2003: 9 апреля</span><span class="sxs-lookup"><span data-stu-id="2dd39-412">Version 2003: April 09</span></span>
<span data-ttu-id="2dd39-413">*Версия 2003 (сборка 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-413">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-415">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-416">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-416">Excel</span></span>

- <span data-ttu-id="2dd39-417">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2dd39-417">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2dd39-418">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2dd39-418">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-419">Outlook</span></span>

- <span data-ttu-id="2dd39-420">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2dd39-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2dd39-421">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2dd39-421">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-422">PowerPoint</span></span>

- <span data-ttu-id="2dd39-423">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2dd39-423">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2dd39-424">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2dd39-424">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-425">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-425">Word</span></span>

- <span data-ttu-id="2dd39-426">**Выбор премиум-контента M365:** оживите свои документы!</span><span class="sxs-lookup"><span data-stu-id="2dd39-426">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2dd39-427">Просматривайте тысячи бесплатных стоковых изображений, значков и наклеек. [Подробнее](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2dd39-427">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-april-03"></a><span data-ttu-id="2dd39-431">Версия 2003: 3 апреля</span><span class="sxs-lookup"><span data-stu-id="2dd39-431">Version 2003: April 03</span></span>
<span data-ttu-id="2dd39-432">*Версия 2003 (сборка 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-432">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-434">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-435">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-435">Excel</span></span>

- <span data-ttu-id="2dd39-436">В некоторых случаях при использовании приложения VBA не работала оценка определенных пользователем функций.</span><span class="sxs-lookup"><span data-stu-id="2dd39-436">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-437">Outlook</span></span>

- <span data-ttu-id="2dd39-438">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="2dd39-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="2dd39-439">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-439">Project</span></span>

- <span data-ttu-id="2dd39-440">При изменении данных предшественника или последователя в представлении формы возникало дополнительное событие ProjectBeforeTaskChangeevent.</span><span class="sxs-lookup"><span data-stu-id="2dd39-440">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-441">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-441">Word</span></span>

- <span data-ttu-id="2dd39-442">Устранена проблема, из-за которой иногда происходил сбой при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="2dd39-442">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-31"></a><span data-ttu-id="2dd39-444">Версия 2003: 31 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-444">Version 2003: March 31</span></span>
<span data-ttu-id="2dd39-445">*Версия 2003 (сборка 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-445">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-447">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-447">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2dd39-448">Access</span><span class="sxs-lookup"><span data-stu-id="2dd39-448">Access</span></span>

- <span data-ttu-id="2dd39-449">**Область задач "Добавление таблиц":** новая область задач Access "Добавление таблиц" наконец доступна!</span><span class="sxs-lookup"><span data-stu-id="2dd39-449">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="2dd39-450">Эта функция позволяет легко выбирать несколько таблиц, которые нужно добавить или удалить в окне запроса, не переходя к диалоговому окну "Отображение таблиц" для запросов и представления связей.</span><span class="sxs-lookup"><span data-stu-id="2dd39-450">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="2dd39-451">Она также включает новую вкладку "Ссылки" для отображения связанных таблиц, поле поиска для фильтрации текущего списка, действие перетаскивания и многое другое!</span><span class="sxs-lookup"><span data-stu-id="2dd39-451">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-454">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-454">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2dd39-455">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-455">Project</span></span>

- <div><span data-ttu-id="2dd39-456"><span style="display:inline !important;">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span></span><span class="sxs-lookup"><span data-stu-id="2dd39-456"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-25"></a><span data-ttu-id="2dd39-458">Версия 2003: 25 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-458">Version 2003: March 25</span></span>
<span data-ttu-id="2dd39-459">*Версия 2003 (сборка 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-459">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="2dd39-460">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2dd39-460">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="2dd39-461">Версия 2003: 23 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-461">Version 2003: March 23</span></span>
<span data-ttu-id="2dd39-462">*Версия 2003 (сборка 12624,20296)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-462">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="2dd39-463">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2dd39-463">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="2dd39-464">Версия 2003: 21 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-464">Version 2003: March 21</span></span>
<span data-ttu-id="2dd39-465">*Версия 2003 (сборка 12624,20276)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-465">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-467">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-467">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-468">Outlook</span></span>

- <span data-ttu-id="2dd39-469">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="2dd39-469">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="2dd39-470">Прикрепив календарь к панели To-Do, присоединяйтесь к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="2dd39-470">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="2dd39-471">**Визуальное обновление календаря:** в прошлом году мы представили вам обновленную почту, а в этом году настала очередь календаря!</span><span class="sxs-lookup"><span data-stu-id="2dd39-471">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="2dd39-472">Обновления свежие, но знакомые, поэтому, как опытный пользователь Outlook, вы можете сразу же подключиться и стать более продуктивным.</span><span class="sxs-lookup"><span data-stu-id="2dd39-472">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-473">PowerPoint</span></span>

- <span data-ttu-id="2dd39-474">**Обновление слайдов во время слайд-шоу.** Слайды, в которые вносят изменения другие авторы, можно обновлять во время презентации.</span><span class="sxs-lookup"><span data-stu-id="2dd39-474">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-16"></a><span data-ttu-id="2dd39-476">Версия 2003: 16 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-476">Version 2003: March 16</span></span>
<span data-ttu-id="2dd39-477">*Версия 2003 (сборка 12624,20224)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-477">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-479">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-480">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-480">Excel</span></span>

- <span data-ttu-id="2dd39-481">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2dd39-481">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-482">Outlook</span></span>

- <span data-ttu-id="2dd39-483">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2dd39-483">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-484">PowerPoint</span></span>

- <span data-ttu-id="2dd39-485">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2dd39-485">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-486">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-486">Word</span></span>

- <span data-ttu-id="2dd39-487">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="2dd39-487">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2dd39-488">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-488">Office Suite</span></span>

- <span data-ttu-id="2dd39-489">**Области с вкладками.** Теперь вы можете переключаться между областями, используя интерфейс вкладок в правой части приложения.</span><span class="sxs-lookup"><span data-stu-id="2dd39-489">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="2dd39-490">Интерфейс отображается только при открытии 2 вкладок и более.</span><span class="sxs-lookup"><span data-stu-id="2dd39-490">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-493">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-494">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-494">Excel</span></span>

- <span data-ttu-id="2dd39-495">Устранена проблема, из-за которой внешние ссылки не обновляются при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="2dd39-495">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-496">Outlook</span></span>

- <span data-ttu-id="2dd39-497">Устранена проблема, из-за которой пользователи могли видеть процесс Outlook, задерживающийся в диспетчере задач после выхода.</span><span class="sxs-lookup"><span data-stu-id="2dd39-497">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2003-march-10"></a><span data-ttu-id="2dd39-499">Версия 2003: 10 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-499">Version 2003: March 10</span></span>
<span data-ttu-id="2dd39-500">*Версия 2003 (сборка 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-500">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="2dd39-501">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2dd39-501">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)
### <a name="feature-updates"></a><span data-ttu-id="2dd39-503">Обновления компонентов</span><span class="sxs-lookup"><span data-stu-id="2dd39-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-504">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-504">Excel</span></span>
- <span data-ttu-id="2dd39-505">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="2dd39-505">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2dd39-506">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-506">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="2dd39-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-507">PowerPoint</span></span>
- <span data-ttu-id="2dd39-508">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="2dd39-508">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2dd39-509">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-509">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="2dd39-510">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-510">Word</span></span>
- <span data-ttu-id="2dd39-511">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="2dd39-511">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2dd39-512">Подробнее</span><span class="sxs-lookup"><span data-stu-id="2dd39-512">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-513">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-514">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-514">Excel</span></span>

- <span data-ttu-id="2dd39-515">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="2dd39-515">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2dd39-516">Исправлена проблема, которая могла возникать при переименовании показателей сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-516">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="2dd39-517">Исправлена проблема, из-за которой текст в срезе неправильно масштабировался в режиме предварительного просмотра.</span><span class="sxs-lookup"><span data-stu-id="2dd39-517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="2dd39-518">Исправлена проблема с производительностью, которая могла возникать при использовании макроса VBA для очистки содержимого диапазона.</span><span class="sxs-lookup"><span data-stu-id="2dd39-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2dd39-519">Исправлена проблема, приводившая к мерцанию интерфейса при выполнении пользователем макроса, взаимодействующего с лентой.</span><span class="sxs-lookup"><span data-stu-id="2dd39-519">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="2dd39-520">Исправлена проблема, из-за которой CSV-файлы загружались неправильно, если первое слово в файле было TABLE.</span><span class="sxs-lookup"><span data-stu-id="2dd39-520">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="2dd39-521">Исправлена проблема, из-за которой мог возникать сбой при переключении пользователей между двумя книгами с разными масштабами.</span><span class="sxs-lookup"><span data-stu-id="2dd39-521">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="2dd39-522">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.</span><span class="sxs-lookup"><span data-stu-id="2dd39-522">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="2dd39-523">Это изменение исправляет ошибку во время выполнения в объектной модели и потенциальный сбой приложения (Excel, Word), если надстройки запрашивают элементы узла в документах или листах, содержащих фигуры с блокировками noSelect.</span><span class="sxs-lookup"><span data-stu-id="2dd39-523">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="2dd39-524">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="2dd39-524">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="2dd39-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-525">Outlook</span></span>

- <span data-ttu-id="2dd39-526">Исправлена проблема, из-за которой правило, созданное с помощью Outlook Web Access, не сохранялось на сервере Exchange Server и возникал конфликт.</span><span class="sxs-lookup"><span data-stu-id="2dd39-526">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="2dd39-527">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="2dd39-527">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="2dd39-528">Исправлена проблема, из-за которой раскрывающийся список не отображается в поле "От" в темном режиме в Outlook.</span><span class="sxs-lookup"><span data-stu-id="2dd39-528">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="2dd39-529">Исправлена проблема, из-за которой в некоторых сценариях Outlook неожиданно создавал выходные данные журнала, даже если ведение журнала было отключено.</span><span class="sxs-lookup"><span data-stu-id="2dd39-529">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="2dd39-530">Исправлена проблема, из-за которой пользователи не могли открывать сообщения из общедоступных папок, если Outlook оставался работать на ночь.</span><span class="sxs-lookup"><span data-stu-id="2dd39-530">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="2dd39-531">Исправлено состояние гонки, при котором кнопки "Разрешить" и "Запретить" на странице разрешений отключались во время проверки подлинности при добавлении учетной записи Gmail.</span><span class="sxs-lookup"><span data-stu-id="2dd39-531">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="2dd39-532">Исправлена проблема, приводившая к утрате пользователями доступа к диалоговому окну разрешений календаря &quot;Параметры доступности&quot;.</span><span class="sxs-lookup"><span data-stu-id="2dd39-532">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="2dd39-533">Исправлена проблема, которая могла привести к появлению оповещения &quot;К сожалению, не удалось открыть элемент&quot; при открытии экземпляров повторяющихся собраний, отправленных из другого часового пояса.</span><span class="sxs-lookup"><span data-stu-id="2dd39-533">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="2dd39-534">Исправлена проблема, из-за которой пользователи не могли повторно открыть MSG-файл после перетаскивания вложения из сообщения.</span><span class="sxs-lookup"><span data-stu-id="2dd39-534">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="2dd39-535">Исправлена проблема, из-за которой после отправки вложенного файла из Outlook в OneDrive имя файла могло изменяться, если имя вложения содержало круглые скобки.</span><span class="sxs-lookup"><span data-stu-id="2dd39-535">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="2dd39-536">Устранена проблема, из-за которой пользователи не могли вложить файл в почтовое сообщение с помощью проводника, если он был открыт в другом приложении.</span><span class="sxs-lookup"><span data-stu-id="2dd39-536">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="2dd39-537">Исправлена проблема, приводившая к сбою Outlook при синхронизации настроек.</span><span class="sxs-lookup"><span data-stu-id="2dd39-537">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2dd39-538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-538">PowerPoint</span></span>

- <span data-ttu-id="2dd39-539">Исправлена проблема, из-за которой рекомендуемые эскизы мигали при наведении указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="2dd39-539">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="2dd39-540">В некоторых случаях это могло приводить к сбою PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2dd39-540">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="2dd39-541">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="2dd39-541">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2dd39-542">Исправлена проблема, которая могла приводить к сбою сохранения документа PowerPoint или Word, содержащего диаграмму Excel.</span><span class="sxs-lookup"><span data-stu-id="2dd39-542">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="2dd39-543">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-543">Project</span></span>

- <span data-ttu-id="2dd39-544">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="2dd39-544">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="2dd39-545">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="2dd39-545">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2dd39-546">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="2dd39-546">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="2dd39-547">Visio</span><span class="sxs-lookup"><span data-stu-id="2dd39-547">Visio</span></span>

- <span data-ttu-id="2dd39-548">В области сведений о фигуре отображались несогласованные данные в разделе "Данные фигуры" в зависимости от файла при открытии в классической версии Visio.</span><span class="sxs-lookup"><span data-stu-id="2dd39-548">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="2dd39-549">Это исправлено.</span><span class="sxs-lookup"><span data-stu-id="2dd39-549">It has now been fixed.</span></span>

- <span data-ttu-id="2dd39-550">Точечные рисунки, импортированные в версиях до 2016, не отображались из-за некоторых проверок безопасности.</span><span class="sxs-lookup"><span data-stu-id="2dd39-550">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="2dd39-551">Эта проблема исправлена в подписке на Visio.</span><span class="sxs-lookup"><span data-stu-id="2dd39-551">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-552">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-552">Word</span></span>

- <span data-ttu-id="2dd39-553">Исправлена проблема, из-за которой карточки примечаний не всегда выделяются при наведении на них указателя мыши.</span><span class="sxs-lookup"><span data-stu-id="2dd39-553">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="2dd39-554">Исправлена проблема, из-за которой при использовании клавиши TAB в карточке примечания не отображалось выделение поля исправления примечания.</span><span class="sxs-lookup"><span data-stu-id="2dd39-554">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="2dd39-555">Исправлена косметическая проблема, из-за которой кнопка "ОК" в диалоговом окне "Файл" в разделе "Параметры" отображалась как неактивная, но ее функциональность не была затронута.</span><span class="sxs-lookup"><span data-stu-id="2dd39-555">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2dd39-556">Во время сеанса совместного редактирования активного документа добавление изображения прямо в карточку примечания могло привести к добавлению тега.</span><span class="sxs-lookup"><span data-stu-id="2dd39-556">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="2dd39-557">Эта проблема исправлена.</span><span class="sxs-lookup"><span data-stu-id="2dd39-557">This issue has been fixed.</span></span>

- <span data-ttu-id="2dd39-558">Вставка элемента управления (например, элемента управления текстовым содержимым) в формулу с последующим сохранением и открытием файла приводит к ошибке с невозможностью прочесть содержимое.</span><span class="sxs-lookup"><span data-stu-id="2dd39-558">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="2dd39-559">Исправлена проблема, из-за которой не удавалось сохранить в облачном хранилище файл, предварительно защищенный паролем.</span><span class="sxs-lookup"><span data-stu-id="2dd39-559">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="2dd39-560">Исправлена проблема с функцией сравнения для документов, защищенных от редактирования.</span><span class="sxs-lookup"><span data-stu-id="2dd39-560">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="2dd39-561">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-561">Office Suite</span></span>

- <span data-ttu-id="2dd39-562">При использовании свойств множественного выбора, просмотра и управляемых метаданных в документах Word, Excel и PowerPoint с сохранением в библиотеке документов SharePoint эти свойства ранее ограничивались 255 знаками.</span><span class="sxs-lookup"><span data-stu-id="2dd39-562">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="2dd39-563">Если они превышали 255 знаков, такие документы не удавалось сохранить.</span><span class="sxs-lookup"><span data-stu-id="2dd39-563">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="2dd39-564">С внесением этого изменения это ограничение было увеличено до 2048 знаков.</span><span class="sxs-lookup"><span data-stu-id="2dd39-564">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="2dd39-565">Исправлена проблема в Word, Excel и PowerPoint, из-за которой в имени участника-пользователя (UPN) больше не учитывается регистр, что привело к уменьшению числа сбоев при работе с файлами в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2dd39-565">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="2dd39-566">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="2dd39-566">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-05"></a><span data-ttu-id="2dd39-568">Версия 2002: 5 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-568">Version 2002: March 05</span></span>
<span data-ttu-id="2dd39-569">*Версия 2002 (сборка 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-569">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="2dd39-570">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2dd39-570">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="2dd39-571">Версия 2002: 4 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-571">Version 2002: March 04</span></span>
<span data-ttu-id="2dd39-572">*Версия 2002 (сборка 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-572">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-574">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-574">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="2dd39-575">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-575">Project</span></span>
- <div><span data-ttu-id="2dd39-576">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="2dd39-576">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="2dd39-577">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-577">Office Suite</span></span>
- <div><span data-ttu-id="2dd39-578">Исправлена проблема, возникавшая при открытии нескольких документов в Word, Excel или PowerPoint из одной библиотеки SharePoint, из-за которой только первый открывавшийся документ проверялся на соответствие политике.</span><span class="sxs-lookup"><span data-stu-id="2dd39-578">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-01"></a><span data-ttu-id="2dd39-580">Версия 2002: 1 марта</span><span class="sxs-lookup"><span data-stu-id="2dd39-580">Version 2002: March 01</span></span>
<span data-ttu-id="2dd39-581">*Версия 2002 (сборка 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-581">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-582">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-583">Outlook</span></span>

- <div><span data-ttu-id="2dd39-584">Исправлена проблема, из-за которой сторонние приложения не могли отправлять электронную почту.</span><span class="sxs-lookup"><span data-stu-id="2dd39-584">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-24"></a><span data-ttu-id="2dd39-586">Версия 2002: 24 февраля</span><span class="sxs-lookup"><span data-stu-id="2dd39-586">Version 2002: February 24</span></span>
<span data-ttu-id="2dd39-587">*Версия 2002 (сборка 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-587">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="2dd39-588">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2dd39-588">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="2dd39-589">Версия 2002: 22 февраля</span><span class="sxs-lookup"><span data-stu-id="2dd39-589">Version 2002: February 22</span></span>
<span data-ttu-id="2dd39-590">*Версия 2002 (сборка 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-590">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="2dd39-591">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="2dd39-591">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="2dd39-592">Версия 2002: 21 февраля</span><span class="sxs-lookup"><span data-stu-id="2dd39-592">Version 2002: February 21</span></span>
<span data-ttu-id="2dd39-593">*Версия 2002 (сборка 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-593">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-595">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-595">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2dd39-596">Access</span><span class="sxs-lookup"><span data-stu-id="2dd39-596">Access</span></span>

- <span data-ttu-id="2dd39-597">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="2dd39-597">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="2dd39-598">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="2dd39-598">Search and replace text in SQL View.</span></span> <span data-ttu-id="2dd39-599">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="2dd39-599">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-600">Outlook</span></span>

- <span data-ttu-id="2dd39-601">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="2dd39-601">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="2dd39-602">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="2dd39-602">Outlook now detects this and helps you get connected.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-605">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-605">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2dd39-606">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-606">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="2dd39-607">Исправлена проблема, из-за которой функция КУБЗНАЧЕНИЕ иногда возвращала неверный результат.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="2dd39-607">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="2dd39-608">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-608">Outlook</span></span>

- <div><span data-ttu-id="2dd39-609">Исправлена проблема, из-за которой запятые в поле месторасположения собрания превращались в точки с запятой.</span><span class="sxs-lookup"><span data-stu-id="2dd39-609">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="2dd39-610">Исправлена проблема, которая могла приводить к сбою при просмотре одного и того же элемента в нескольких окнах.</span><span class="sxs-lookup"><span data-stu-id="2dd39-610">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="2dd39-611">Исправлена проблема, из-за которой приложение Outlook неожиданно синхронизировало всю почту, даже если ползунок синхронизация настроен на меньшее значение.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="2dd39-611">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="2dd39-612">Исправлена проблема, из-за которой для пользователей с черной темой в раскрывающемся списке &quot;От&quot; отображался белый текст на белом фоне.</span><span class="sxs-lookup"><span data-stu-id="2dd39-612">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="2dd39-613"><span style="display:inline !important;">Это изменение восстанавливает возможность просмотра многострочных тем в заголовке сообщения.</span></span><span class="sxs-lookup"><span data-stu-id="2dd39-613"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-18"></a><span data-ttu-id="2dd39-615">Версия 2002: 18 февраля</span><span class="sxs-lookup"><span data-stu-id="2dd39-615">Version 2002: February 18</span></span>
<span data-ttu-id="2dd39-616">*Версия 2002 (сборка 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-616">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="2dd39-617">Версия 2002:11 февраля</span><span class="sxs-lookup"><span data-stu-id="2dd39-617">Version 2002: February 11</span></span>
<span data-ttu-id="2dd39-618">*Версия 2002 (сборка 12527,20092)*</span><span class="sxs-lookup"><span data-stu-id="2dd39-618">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="2dd39-619">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2dd39-619">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="2dd39-621">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="2dd39-621">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2dd39-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-622">Outlook</span></span>

- <span data-ttu-id="2dd39-623">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="2dd39-623">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="2dd39-624">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-624">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="2dd39-625">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-625">Word</span></span>

- <span data-ttu-id="2dd39-626">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="2dd39-626">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2dd39-627">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-627">Office Suite</span></span>

- <span data-ttu-id="2dd39-628">**Более понятные значки строки состояния:** значки строки состояния стали понятнее.</span><span class="sxs-lookup"><span data-stu-id="2dd39-628">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="2dd39-631">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="2dd39-631">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2dd39-632">Access</span><span class="sxs-lookup"><span data-stu-id="2dd39-632">Access</span></span>

- <span data-ttu-id="2dd39-633">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="2dd39-633">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2dd39-634">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="2dd39-634">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="2dd39-635">Это обновление исправляет проблему, из-за которой использование объекта ADODB</span><span class="sxs-lookup"><span data-stu-id="2dd39-635">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2dd39-636">средства записи в коде VB могло неверно вызывать сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="2dd39-636">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2dd39-637">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных.</span><span class="sxs-lookup"><span data-stu-id="2dd39-637">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="2dd39-638">Excel</span><span class="sxs-lookup"><span data-stu-id="2dd39-638">Excel</span></span>

- <span data-ttu-id="2dd39-639">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="2dd39-639">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="2dd39-640">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="2dd39-640">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="2dd39-641">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при использовании параметра "Текст по столбцам" с динамическими массивами.</span><span class="sxs-lookup"><span data-stu-id="2dd39-641">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="2dd39-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="2dd39-642">Outlook</span></span>

- <span data-ttu-id="2dd39-643">Исправлена проблема, из-за которой при прокручивании календаря в представлении "Месяц" не отображались предыдущие события календаря.</span><span class="sxs-lookup"><span data-stu-id="2dd39-643">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="2dd39-644">Папки, сохраненные в разделе "Избранное" в области навигации слева, могут периодически исчезать.</span><span class="sxs-lookup"><span data-stu-id="2dd39-644">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="2dd39-645">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при попытке указать недопустимый адрес.</span><span class="sxs-lookup"><span data-stu-id="2dd39-645">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="2dd39-646">Устранена проблема, из-за которой опция отключения подсветки помеченных элементов не учитывалась в некоторых сценариях.</span><span class="sxs-lookup"><span data-stu-id="2dd39-646">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2dd39-647">Эта проблема связана с проблемой, из-за которой пользователи могут столкнуться со сбоем при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="2dd39-647">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="2dd39-648">Исправлена проблема, из-за которой срок действия почты в соответствии с политикой хранения будет иметь две метки.</span><span class="sxs-lookup"><span data-stu-id="2dd39-648">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="2dd39-649">Один показывает, что срок действия письма истекает через один день, а другой - что срок его действия истекает через два дня.</span><span class="sxs-lookup"><span data-stu-id="2dd39-649">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="2dd39-650">Устранена проблема, приводившая к сбоям пользователей при просмотре более 30 календарей в среде Citrix.</span><span class="sxs-lookup"><span data-stu-id="2dd39-650">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2dd39-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2dd39-651">PowerPoint</span></span>

- <span data-ttu-id="2dd39-652">Исправлена проблема, из-за которой рукописные фрагменты могли не отображаться полностью или пропускаться при использовании анимации рукописного ввода в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2dd39-652">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="2dd39-653">Исправлена ошибка, из-за которой после закрытия файла PowerPoint не сразу удалял его из коллекции презентаций, если были запущены какие-либо обработчики событий.</span><span class="sxs-lookup"><span data-stu-id="2dd39-653">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="2dd39-654">Поэтому число открытых презентаций, указываемых объектной моделью, является неверным, и запрещается завершение работы PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2dd39-654">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="2dd39-655">Исправлена проблема с выделением: белый текст с темными цветами выделения печатается как черный в оттенках серого.</span><span class="sxs-lookup"><span data-stu-id="2dd39-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="2dd39-656">Project</span><span class="sxs-lookup"><span data-stu-id="2dd39-656">Project</span></span>

- <span data-ttu-id="2dd39-657">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="2dd39-657">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="2dd39-658">Word</span><span class="sxs-lookup"><span data-stu-id="2dd39-658">Word</span></span>

- <span data-ttu-id="2dd39-659">При обновлении и прокрутке оглавления иногда отображается серая область над документом.</span><span class="sxs-lookup"><span data-stu-id="2dd39-659">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="2dd39-660">Исправлена проблема, из-за которой не работала кнопка "Обзор" при сохранении файла, если примечание написано, но не опубликовано, а пользователь попытался сохранить файл.</span><span class="sxs-lookup"><span data-stu-id="2dd39-660">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="2dd39-661">Исправлена проблема, из-за которой при переходе между карточками примечаний иногда отображалось изначально выбранное примечание с выделением выбора.</span><span class="sxs-lookup"><span data-stu-id="2dd39-661">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="2dd39-662">Исправлена ошибка, из-за которой форматирование курсива терялось после редактирования комментария, выделения курсивом текста и последующей публикации.</span><span class="sxs-lookup"><span data-stu-id="2dd39-662">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="2dd39-663">Исправлена проблема, из-за которой подсказки примечаний не были видны в режиме чтения с помощью инвертированного цвета страницы.</span><span class="sxs-lookup"><span data-stu-id="2dd39-663">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="2dd39-664">Исправлена проблема, из-за которой при совместном редактировании документа черновик корневого примечания мог не сохраняться.</span><span class="sxs-lookup"><span data-stu-id="2dd39-664">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="2dd39-665">Если включена функция SlideTrack, а область примечаний закрыта, сочетание клавиш CTRL+ALT+M иногда не открывает область примечаний.</span><span class="sxs-lookup"><span data-stu-id="2dd39-665">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="2dd39-666">Исправлена проблема, из-за которой добавление @упоминания в таблицу могло вызывать сообщение об ошибке: "Таблица в документе повреждена".</span><span class="sxs-lookup"><span data-stu-id="2dd39-666">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="2dd39-667">Исправлена ошибка, из-за которой команды комментария (Редактировать комментарий, Ответить на комментарий, Удалить комментарий, Разрешить комментарий) в контекстном меню комментариев не отображались.</span><span class="sxs-lookup"><span data-stu-id="2dd39-667">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2dd39-668">Набор Office</span><span class="sxs-lookup"><span data-stu-id="2dd39-668">Office Suite</span></span>

- <span data-ttu-id="2dd39-669">Исправлена проблема, которая могла приводить к неправильной установке пакета средств проверки правописания для норвежского (нюнорск) языка (nn-no).</span><span class="sxs-lookup"><span data-stu-id="2dd39-669">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="2dd39-670">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="2dd39-670">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

