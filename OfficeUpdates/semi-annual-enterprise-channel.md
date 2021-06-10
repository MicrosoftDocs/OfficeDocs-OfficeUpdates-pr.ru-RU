---
title: Заметки о выпусках Полугодового канала (корпоративный)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Этот раздел содержит заметки о выпусках Semi-Annual Channel для подписки "Приложения Microsoft 365" для ИТ-специалистов.
ms.openlocfilehash: a2b8ae060b7be521bb60f86b809ca0be0bd10817
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/09/2021
ms.locfileid: "52851959"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="657f5-103">Заметки о выпусках Полугодового канала (корпоративный)</span><span class="sxs-lookup"><span data-stu-id="657f5-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="657f5-104">Эти заметки о выпусках содержат информацию о новых возможностях и обновлениях, не связанных с безопасностью, которые включены в Полугодовой канал (корпоративный) для подписок "Приложения Microsoft 365 для предприятий", "Приложения Microsoft 365 для бизнеса", а также эквивалентов классических приложений для Project и Visio, предоставляемых по подписке.</span><span class="sxs-lookup"><span data-stu-id="657f5-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!NOTE]
>
>- <span data-ttu-id="657f5-105">OneNote 2016 включается по умолчанию, если пользователь, для которого применяется Полугодовой канал (корпоративный), скачивает "Приложения Microsoft 365" на портале Office и устанавливает в Windows 10.</span><span class="sxs-lookup"><span data-stu-id="657f5-105">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-june-08"></a><span data-ttu-id="657f5-107">Версия 2008: 8 июня</span><span class="sxs-lookup"><span data-stu-id="657f5-107">Version 2008: June 08</span></span>
<span data-ttu-id="657f5-108">*Версия 2008 (сборка 13127.21668)*</span><span class="sxs-lookup"><span data-stu-id="657f5-108">*Version 2008 (Build 13127.21668)*</span></span>

<span data-ttu-id="657f5-109">Обновления для системы безопасности перечислены [здесь](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-109">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-111">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-112">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-112">Excel</span></span>

- <span data-ttu-id="657f5-113">Исправлена проблема, из-за которой в списке надстроек Excel для некоторых пользователей отображались дополнительные записи.</span><span class="sxs-lookup"><span data-stu-id="657f5-113">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="657f5-114">Исправлена проблема, из-за которой в строке состояния не указывалось состояние готовности для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="657f5-114">We fixed an issue that caused the Status Bar to not indicate a Ready state for some users.</span></span>


### <a name="word"></a><span data-ttu-id="657f5-115">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-115">Word</span></span>

- <span data-ttu-id="657f5-116">Исправлена проблема, из-за которой при вставке текста с помощью пользовательских стилей нумерация и отступы были потеряны.</span><span class="sxs-lookup"><span data-stu-id="657f5-116">Fixed an issue where numbering and indents were lost when pasting text with custom styles.</span></span>


- <span data-ttu-id="657f5-117">Исправлена проблема, из-за которой удалялось ограничение на размер строк, разрешенных для элементов управления содержимым.</span><span class="sxs-lookup"><span data-stu-id="657f5-117">Fixed an issue which removes limit on size of strings allowed for content controls.</span></span>


### <a name="office-suite"></a><span data-ttu-id="657f5-118">Набор Office</span><span class="sxs-lookup"><span data-stu-id="657f5-118">Office Suite</span></span>

- <span data-ttu-id="657f5-119">До этого изменения шаблоны Office отображались, даже если объект групповой политики для их отключения был включен.</span><span class="sxs-lookup"><span data-stu-id="657f5-119">Before this change, Office templates were displaying even if GPO for disabling them was turned on.</span></span> <span data-ttu-id="657f5-120">Благодаря этому изменению шаблоны теперь правильно учитывают объекты групповой политики и отображают/скрывают их по запросу.</span><span class="sxs-lookup"><span data-stu-id="657f5-120">With this change, templates now honor the GPO correctly and display/hide as requested.</span></span>


- <span data-ttu-id="657f5-121">Исправлена редкая проблема, из-за которой открытие файлов из SharePoint Online могло без необходимости откладываться из-за времени ожидания, заданного лицензированием и управлением цифровыми правами.</span><span class="sxs-lookup"><span data-stu-id="657f5-121">Fixed a rare issue where opening files from SharePoint Online could be unnecessarily delayed by Licensing and Digital Rights Management experiencing timeouts.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-june-08"></a><span data-ttu-id="657f5-123">Версия 2002: 8 июня</span><span class="sxs-lookup"><span data-stu-id="657f5-123">Version 2002: June 08</span></span>
<span data-ttu-id="657f5-124">*Версия 2002 (сборка 12527.21952)*</span><span class="sxs-lookup"><span data-stu-id="657f5-124">*Version 2002 (Build 12527.21952)*</span></span>

<span data-ttu-id="657f5-125">Обновления для системы безопасности перечислены [здесь](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-125">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-127">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-127">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-128">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-128">Excel</span></span>

- <span data-ttu-id="657f5-129">Исправлена проблема, из-за которой в списке надстроек Excel для некоторых пользователей отображались дополнительные записи.</span><span class="sxs-lookup"><span data-stu-id="657f5-129">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-may-11"></a><span data-ttu-id="657f5-131">Версия 2008: 11 мая</span><span class="sxs-lookup"><span data-stu-id="657f5-131">Version 2008: May 11</span></span>
<span data-ttu-id="657f5-132">*Версия 2008 (сборка 13127.21624)*</span><span class="sxs-lookup"><span data-stu-id="657f5-132">*Version 2008 (Build 13127.21624)*</span></span>

<span data-ttu-id="657f5-133">Обновления для системы безопасности перечислены [здесь](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-133">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-135">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-136">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-136">Excel</span></span>

- <span data-ttu-id="657f5-137">Исправлена проблема, из-за которой не загружались некоторые надстройки для автоматизации Excel.</span><span class="sxs-lookup"><span data-stu-id="657f5-137">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="657f5-138">Исправлена проблема, из-за которой не удавалось вставлять формулы на защищенном листе.</span><span class="sxs-lookup"><span data-stu-id="657f5-138">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


- <span data-ttu-id="657f5-139">Мы внесли исправление, чтобы повысить производительность при переключении между листами или прокрутке со включенной специальной возможностью отслеживания фокусировки.</span><span class="sxs-lookup"><span data-stu-id="657f5-139">We made a fix to improve performance while switching between sheets or scrolling with accessibility focus tracking turned on.</span></span>


- <span data-ttu-id="657f5-140">Исправлена проблема, из-за которой при рукописном вводе приложение Excel переставало отвечать на запросы.</span><span class="sxs-lookup"><span data-stu-id="657f5-140">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="657f5-141">Outlook</span><span class="sxs-lookup"><span data-stu-id="657f5-141">Outlook</span></span>

- <span data-ttu-id="657f5-142">Устранена проблема, из-за которой письма отправлялись с цифровой подписью после того, как пользователь снимал этот флажок.</span><span class="sxs-lookup"><span data-stu-id="657f5-142">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="word"></a><span data-ttu-id="657f5-143">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-143">Word</span></span>

- <span data-ttu-id="657f5-144">Устранена проблема, из-за которой не удавалось экспортировать некоторые файлы в формате PDF.</span><span class="sxs-lookup"><span data-stu-id="657f5-144">Fixes an issue where some files were not able to be exported as PDF.</span></span>



[//]: # (НЕ УДАЛЯЙТЕ СВЕДЕНИЯ ОБ ОШИБКАХ (КОНЕЦ СОДЕРЖИМОГО))

## <a name="version-2002-may-11"></a><span data-ttu-id="657f5-146">Версия 2002: 11 мая</span><span class="sxs-lookup"><span data-stu-id="657f5-146">Version 2002: May 11</span></span>
<span data-ttu-id="657f5-147">*Версия 2002 (сборка 12527.21912)*</span><span class="sxs-lookup"><span data-stu-id="657f5-147">*Version 2002 (Build 12527.21912)*</span></span>

<span data-ttu-id="657f5-148">Обновления для системы безопасности перечислены [здесь](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-148">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-150">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-150">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-151">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-151">Excel</span></span>

- <span data-ttu-id="657f5-152">Исправлена проблема, из-за которой не загружались некоторые надстройки для автоматизации Excel.</span><span class="sxs-lookup"><span data-stu-id="657f5-152">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2008-april-13"></a><span data-ttu-id="657f5-154">Версия 2008: 13 апреля</span><span class="sxs-lookup"><span data-stu-id="657f5-154">Version 2008: April 13</span></span>
<span data-ttu-id="657f5-155">*Версия 2008 (сборка 13127.21506)*</span><span class="sxs-lookup"><span data-stu-id="657f5-155">*Version 2008 (Build 13127.21506)*</span></span>

<span data-ttu-id="657f5-156">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="657f5-156">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-158">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-158">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-159">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-159">Excel</span></span>

- <span data-ttu-id="657f5-160">Исправлена проблема, из-за которой форматирование сводной таблицы приводило к повреждению книги при сохранении в формате XLS или XLT.</span><span class="sxs-lookup"><span data-stu-id="657f5-160">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="657f5-161">Исправлена проблема, из-за которой неожиданно отображались некоторые заметки при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="657f5-161">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


### <a name="outlook"></a><span data-ttu-id="657f5-162">Outlook</span><span class="sxs-lookup"><span data-stu-id="657f5-162">Outlook</span></span>

- <span data-ttu-id="657f5-163">Исправлена проблема, из-за которой пользователи, имеющие общие или делегированные почтовые ящики с разветвленной иерархией в профиле, сталкивались с зависанием.</span><span class="sxs-lookup"><span data-stu-id="657f5-163">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="657f5-164">Исправлена проблема, из-за которой некоторые пользователи сталкивались с непредвиденным закрытием при синхронизации почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="657f5-164">We fixed an issue that caused some users to experiences an unexpected closure when syncing their mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="657f5-165">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="657f5-165">PowerPoint</span></span>

- <span data-ttu-id="657f5-166">Исправлена проблема, из-за которой приложения Office переставали отвечать после открытия карточки пользователя и перехода к другому приложению.</span><span class="sxs-lookup"><span data-stu-id="657f5-166">We fixed an issue that caused users to see Office applications become unresponsive after bringing up a person card and navigating to another application.</span></span>


### <a name="word"></a><span data-ttu-id="657f5-167">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-167">Word</span></span>

- <span data-ttu-id="657f5-168">Исправлена проблема, из-за которой встроенная кнопка метки конфиденциальности затенялась при сохранении и повторном открытии документа Word.</span><span class="sxs-lookup"><span data-stu-id="657f5-168">Fixes an issue where the built-in Sensitivity Label button is greyed out when saving a Word doc and reopening.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-april-13"></a><span data-ttu-id="657f5-170">Версия 2002: 13 апреля</span><span class="sxs-lookup"><span data-stu-id="657f5-170">Version 2002: April 13</span></span>
<span data-ttu-id="657f5-171">*Версия 2002 (сборка 12527.21814)*</span><span class="sxs-lookup"><span data-stu-id="657f5-171">*Version 2002 (Build 12527.21814)*</span></span>

<span data-ttu-id="657f5-172">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="657f5-172">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2008-march-09"></a><span data-ttu-id="657f5-173">Версия 2008: 9 марта</span><span class="sxs-lookup"><span data-stu-id="657f5-173">Version 2008: March 09</span></span>
<span data-ttu-id="657f5-174">*Версия 2008 (сборка 13127.21348)*</span><span class="sxs-lookup"><span data-stu-id="657f5-174">*Version 2008 (Build 13127.21348)*</span></span>

<span data-ttu-id="657f5-175">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-175">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-177">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-177">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-178">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-178">Excel</span></span>

- <span data-ttu-id="657f5-179">Устранена проблема, из-за которой приложение Excel переставало отвечать после выбора ряда данных в диаграмме.</span><span class="sxs-lookup"><span data-stu-id="657f5-179">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="657f5-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="657f5-180">PowerPoint</span></span>

- <span data-ttu-id="657f5-181">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="657f5-181">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="657f5-182">Исправлена проблема, из-за которой в некоторых сценариях выбор идеи оформления удаляет метку классификации данных в презентации.</span><span class="sxs-lookup"><span data-stu-id="657f5-182">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases</span></span>


### <a name="word"></a><span data-ttu-id="657f5-183">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-183">Word</span></span>

- <span data-ttu-id="657f5-184">Исправлена проблема, из-за которой приложение могло неожиданно завершать работу при сбое сохранения документа.</span><span class="sxs-lookup"><span data-stu-id="657f5-184">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="657f5-185">Набор Office</span><span class="sxs-lookup"><span data-stu-id="657f5-185">Office Suite</span></span>

- <span data-ttu-id="657f5-186">Исправлена проблема, из-за которой при копировании и вставке сообщений в Skype для бизнеса отображалось диалоговое окно "Произошла ошибка при вставке содержимого".</span><span class="sxs-lookup"><span data-stu-id="657f5-186">Fixed an issue where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-march-09"></a><span data-ttu-id="657f5-188">Версия 2002: 9 марта</span><span class="sxs-lookup"><span data-stu-id="657f5-188">Version 2002: March 09</span></span>
<span data-ttu-id="657f5-189">*Версия 2002 (сборка 12527.21686)*</span><span class="sxs-lookup"><span data-stu-id="657f5-189">*Version 2002 (Build 12527.21686)*</span></span>

<span data-ttu-id="657f5-190">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-190">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2008-february-09"></a><span data-ttu-id="657f5-191">Версия 2008: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="657f5-191">Version 2008: February 09</span></span>
<span data-ttu-id="657f5-192">*Версия 2008 (сборка 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="657f5-192">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="657f5-193">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-193">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-195">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-195">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-196">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-196">Excel</span></span>

- <span data-ttu-id="657f5-197">Исправлена проблема, из-за которой приложение Excel неожиданно закрывалось при открытии файлов UNC с недопустимыми атрибутами файлов (время создания, время изменения и т. д.)</span><span class="sxs-lookup"><span data-stu-id="657f5-197">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="657f5-198">Исправлена проблема, из-за которой не осуществлялся перенос параметров десятичных разделителей и разделителей групп разрядов при копировании диаграммы из Excel и ее вставке в Word или PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="657f5-198">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="657f5-199">Исправлена проблема, из-за которой производительность выполнения макроса, включающего форматирование диапазона сводной таблицы, снижалась при каждом его выполнении.</span><span class="sxs-lookup"><span data-stu-id="657f5-199">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="657f5-200">Исправлена проблема, из-за которой удалялись правила условного форматирования при копировании или перемещении листов в другую книгу.</span><span class="sxs-lookup"><span data-stu-id="657f5-200">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="657f5-201">Исправлена проблема, из-за которой пользователи не могли применять метки конфиденциальности к файлам Excel, если при загрузке приложения был отключен начальный экран.</span><span class="sxs-lookup"><span data-stu-id="657f5-201">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="657f5-202">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="657f5-202">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="657f5-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="657f5-203">Outlook</span></span>

- <span data-ttu-id="657f5-204">Исправлена проблема, приводившая к эпизодическому прекращению работы Outlook при добавлении или сохранении вложений.</span><span class="sxs-lookup"><span data-stu-id="657f5-204">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="657f5-205">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="657f5-205">PowerPoint</span></span>

- <span data-ttu-id="657f5-206">Исправлена проблема, из-за которой команда размера шрифта, добавленная QAT, автоматически выполнялась для ближайшего определенного размера шрифта при ее обновлении.</span><span class="sxs-lookup"><span data-stu-id="657f5-206">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="657f5-207">Исправлена проблема, из-за которой при копировании и вставке слайда с использованием параметра "Сохранить исходное форматирование" иногда неожиданно выполнялось копирование поверх нового образца слайдов</span><span class="sxs-lookup"><span data-stu-id="657f5-207">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="657f5-208">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-208">Word</span></span>

- <span data-ttu-id="657f5-209">Исправлена проблема с отслеживанием изменений, из-за которой иногда при открытии документа Word могло появляться диалоговое окно с сообщением об ошибке.</span><span class="sxs-lookup"><span data-stu-id="657f5-209">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="657f5-210">Исправлена проблема с открытием облачного файла из папки синхронизации OneDrive.</span><span class="sxs-lookup"><span data-stu-id="657f5-210">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="657f5-211">Набор Office</span><span class="sxs-lookup"><span data-stu-id="657f5-211">Office Suite</span></span>

- <span data-ttu-id="657f5-212">Исправлена проблема, не позволявшая открыть файл в Office.</span><span class="sxs-lookup"><span data-stu-id="657f5-212">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="657f5-213">Исправлена проблема, из-за которой могли повреждаться документы, содержащие эскизные контуры, примененные к соединителям с помощью форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="657f5-213">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-february-09"></a><span data-ttu-id="657f5-215">Версия 2002: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="657f5-215">Version 2002: February 09</span></span>
<span data-ttu-id="657f5-216">*Версия 2002 (сборка 12527.21594)*</span><span class="sxs-lookup"><span data-stu-id="657f5-216">*Version 2002 (Build 12527.21594)*</span></span>

<span data-ttu-id="657f5-217">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-217">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-219">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-219">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="657f5-220">Набор Office</span><span class="sxs-lookup"><span data-stu-id="657f5-220">Office Suite</span></span>

- <span data-ttu-id="657f5-221">Исправлена проблема, из-за которой могли повреждаться документы, содержащие эскизные контуры, примененные к соединителям с помощью форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="657f5-221">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-february-09"></a><span data-ttu-id="657f5-223">Версия 1908: 9 февраля</span><span class="sxs-lookup"><span data-stu-id="657f5-223">Version 1908: February 09</span></span>
<span data-ttu-id="657f5-224">*Версия 1908 (сборка 11929.21008)*</span><span class="sxs-lookup"><span data-stu-id="657f5-224">*Version 1908 (Build 11929.21008)*</span></span>

<span data-ttu-id="657f5-225">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-225">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2008-january-12"></a><span data-ttu-id="657f5-226">Версия 2008: 12 января</span><span class="sxs-lookup"><span data-stu-id="657f5-226">Version 2008: January 12</span></span>
<span data-ttu-id="657f5-227">*Версия 2008 (сборка 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="657f5-227">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="657f5-228">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-228">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="657f5-230">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="657f5-230">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="657f5-231">Access</span><span class="sxs-lookup"><span data-stu-id="657f5-231">Access</span></span>

- <span data-ttu-id="657f5-232">**Повышайте эффективность работы в конструкторе запросов, режиме SQL и окне "Схема данных".** Щелкните правой кнопкой мыши таблицу для ее открытия, проектирования, изменения размера или скрытия.</span><span class="sxs-lookup"><span data-stu-id="657f5-232">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="657f5-233">Находите и заменяйте текст в режиме SQL.</span><span class="sxs-lookup"><span data-stu-id="657f5-233">Search and replace text in SQL View.</span></span> <span data-ttu-id="657f5-234">Выделяйте несколько таблиц в окне схемы данных.</span><span class="sxs-lookup"><span data-stu-id="657f5-234">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="657f5-235">**Быстрое добавление таблиц.** Используйте область задач "Добавление таблиц", которая остается открытой во время работы, чтобы добавлять таблицы в связи и запросы.</span><span class="sxs-lookup"><span data-stu-id="657f5-235">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="657f5-236">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-236">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="657f5-237">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-237">Excel</span></span>

- <span data-ttu-id="657f5-238">**Ваши любимые функции Excel теперь работают быстрее.** Функции СУММЕСЛИМН, СРЗНАЧЕСЛИМН, СЧЁТЕСЛИМН, МАКСЕСЛИМН и МИНЕСЛИМН теперь работают намного быстрее.</span><span class="sxs-lookup"><span data-stu-id="657f5-238">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="657f5-239">Быстрее переходите к итоговой строке.</span><span class="sxs-lookup"><span data-stu-id="657f5-239">Get to the bottom line more quickly.</span></span> <span data-ttu-id="657f5-240">Попробуйте уже сейчас.</span><span class="sxs-lookup"><span data-stu-id="657f5-240">Try one now.</span></span>

- <span data-ttu-id="657f5-241">**Улучшение функции Realtimedata (RTD):** В Office 365 версии 2002 канала Monthly channel или более поздних версиях функция Excel RealTimeData (ДРВ) работает гораздо быстрее, чем в вычисление данных в таблице в Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="657f5-241">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="657f5-242">Мы удалили узкие места в базовой памяти и структурах данных, а также обеспечили потокобезопасность, чтобы разрешить вычисление во всех доступных потоках многопоточного пересчета (MTR).</span><span class="sxs-lookup"><span data-stu-id="657f5-242">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

- <span data-ttu-id="657f5-243">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="657f5-243">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="657f5-244">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-244">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="657f5-245">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="657f5-245">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="657f5-246">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="657f5-246">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="657f5-247">**Создание сводных таблиц на основе наборов данных в Power BI.** В Excel несколькими щелчками мыши можно создавать сводные таблицы, подключенные к хранящимся в Power BI наборам данных.</span><span class="sxs-lookup"><span data-stu-id="657f5-247">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="657f5-248">Это позволит вам наиболее эффективно использовать и сводные таблицы, и Power BI.</span><span class="sxs-lookup"><span data-stu-id="657f5-248">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="657f5-249">Производите вычисления с данными защищенных наборов данных Power BI, обобщайте и анализируйте их с помощью сводных таблиц.</span><span class="sxs-lookup"><span data-stu-id="657f5-249">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="657f5-250">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-250">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="657f5-251">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="657f5-251">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="657f5-252">Outlook</span><span class="sxs-lookup"><span data-stu-id="657f5-252">Outlook</span></span>

- <span data-ttu-id="657f5-253">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="657f5-253">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="657f5-254">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="657f5-254">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="657f5-255">**Обновления Календаря.** Ознакомьтесь с наглядными обновлениями, упрощающими сканирование календаря.</span><span class="sxs-lookup"><span data-stu-id="657f5-255">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="657f5-256">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-256">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="657f5-257">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="657f5-257">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="657f5-258">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="657f5-258">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="657f5-259">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="657f5-259">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="657f5-260">**Перетаскивайте письма в вашу собственную группу.** Перемещайте и копируйте сообщения и беседы, перетаскивая их из папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="657f5-260">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="657f5-261">Общий доступ к перенесенным сообщениям будет предоставляться всем участникам группы.</span><span class="sxs-lookup"><span data-stu-id="657f5-261">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="657f5-262">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="657f5-262">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="657f5-263">**Присоединяйтесь к собраниям, не выходя из папки Входящие:** не нужно переключаться на календарь, чтобы присоединиться к онлайн-собраниям.</span><span class="sxs-lookup"><span data-stu-id="657f5-263">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="657f5-264">Если календарь закреплен на панели задач, учетные записи пользователей, размещенные в Exchange Server 2019 или Exchange Online, могут присоединиться к любому собранию одним щелчком мыши.</span><span class="sxs-lookup"><span data-stu-id="657f5-264">With the Calendar pinned to the To-Do pane, user accounts hosted on Exchange Server 2019 or Exchange Online can join any meeting with just one click.</span></span> [<span data-ttu-id="657f5-265">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-265">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="657f5-266">**Новый интерфейс для сетей Wi-Fi с авторизацией.** Вам приходилось присоединяться к сети Wi-Fi с обязательной веб-страницей для входа?</span><span class="sxs-lookup"><span data-stu-id="657f5-266">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="657f5-267">Теперь Outlook обнаруживает это и помогает вам подключиться.</span><span class="sxs-lookup"><span data-stu-id="657f5-267">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="657f5-268">Дополнительные сведения см. в этой [публикации в блоге](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="657f5-268">See details in [blog post](https://insider.office.com/ru-RU/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="657f5-269">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="657f5-269">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="657f5-270">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-270">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="657f5-271">**Лучшие результаты - в одно мгновение:** мы обновили возможности поиска, чтобы сделать их умнее, быстрее и надежнее, чем когда-либо.</span><span class="sxs-lookup"><span data-stu-id="657f5-271">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="657f5-272">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-272">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="powerpoint"></a><span data-ttu-id="657f5-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="657f5-273">PowerPoint</span></span>

- <span data-ttu-id="657f5-274">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="657f5-274">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="657f5-275">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="657f5-275">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="657f5-276">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-276">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="657f5-277">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="657f5-277">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="657f5-278">**Ссылка на слайд:** попросите коллег поучаствовать в создании презентации и направьте их прямо на нужный слайд.</span><span class="sxs-lookup"><span data-stu-id="657f5-278">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="657f5-279">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-279">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="657f5-280">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="657f5-280">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="657f5-281">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="657f5-281">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="657f5-282">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="657f5-282">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="657f5-283">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="657f5-283">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="657f5-284">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-284">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="657f5-285">**Улучшенные диаграммы.** Более удобное создание диаграмм от руки за счет использования улучшенных соединителей и более совершенного процесса преобразования рукописного ввода.</span><span class="sxs-lookup"><span data-stu-id="657f5-285">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="657f5-286">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-286">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="657f5-287">**Улучшена производительность потокового видео в PowerPoint.** Мы улучшили скорость воспроизведения в видеороликах Microsoft Stream, чтобы сократить время загрузки видео и обеспечить удобство просмотра.</span><span class="sxs-lookup"><span data-stu-id="657f5-287">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="657f5-288">Используйте корпоративные видео из Microsoft Stream для улучшения презентаций.</span><span class="sxs-lookup"><span data-stu-id="657f5-288">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

- <span data-ttu-id="657f5-p120">**Привлечение внимания с помощью \@упоминаний.** Добавляйте @упоминания в примечания, оповещая коллег, что требуется их участие. [Подробнее](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="657f5-p120">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>

- <span data-ttu-id="657f5-291">**Синхронизировать изменения во время презентации:** Синхронизируйте изменения всякий раз, когда они вносятся, даже когда презентация находится в режиме слайд-шоу.</span><span class="sxs-lookup"><span data-stu-id="657f5-291">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="657f5-292">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-292">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="657f5-293">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="657f5-293">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="657f5-294">**Комментарии.** Новые функций комментирования в PowerPoint позволяют быстро и легко находить и добавлять комментарии к документам.</span><span class="sxs-lookup"><span data-stu-id="657f5-294">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="657f5-295">Модернизируйте совместную работу с помощью новых функций, таких как привязка комментариев, сопоставление, задачи, улучшенные уведомления об упоминаниях и т. д.</span><span class="sxs-lookup"><span data-stu-id="657f5-295">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="657f5-296">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-296">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

### <a name="word"></a><span data-ttu-id="657f5-297">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-297">Word</span></span>

- <span data-ttu-id="657f5-298">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="657f5-298">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="657f5-299">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="657f5-299">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="657f5-300">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-300">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="657f5-301">**Выберите идеальный цвет.** Используйте шестнадцатеричные коды цветов, чтобы выбрать нужный цвет шрифта, выделения текста и т. д.</span><span class="sxs-lookup"><span data-stu-id="657f5-301">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="657f5-302">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="657f5-302">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="657f5-303">**Улучшенные диаграммы с картами.** Мы улучшили диаграммы с картами, интегрировав в них географические типы данных Excel, предоставляющие обширные сведения о расположениях на карте.</span><span class="sxs-lookup"><span data-stu-id="657f5-303">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="657f5-304">Подробнее</span><span class="sxs-lookup"><span data-stu-id="657f5-304">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="657f5-305">**Подтверждение действий в средстве чтения с экрана.** Подтверждение действий — это важное требование для обеспечения специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="657f5-305">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="657f5-306">С появлением нового API уведомлений из Windows мы можем оповещать пользователей средства чтения с экрана об успехе их действий.</span><span class="sxs-lookup"><span data-stu-id="657f5-306">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="657f5-307">Теперь пользователи экранного диктора в Word для Win32 уведомляются о вырезании, копировании, вставке, использовании полужирного шрифта, курсива или подчеркивания, отмене, повторе, автозамене и автоматическом использовании прописных букв.</span><span class="sxs-lookup"><span data-stu-id="657f5-307">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="657f5-308">Чтобы включить эту возможность, включите экранный диктор с помощью клавиш Windows+CTRL+ВВОД.</span><span class="sxs-lookup"><span data-stu-id="657f5-308">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="657f5-309">Дополнительные сведения см. в этой [публикации в блоге](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="657f5-309">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="657f5-310">Набор Office</span><span class="sxs-lookup"><span data-stu-id="657f5-310">Office Suite</span></span>

- <span data-ttu-id="657f5-311">**Метки конфиденциальности**. Теперь вы можете применять метку конфиденциальности, настроенную организацией для запроса пользовательских разрешений.</span><span class="sxs-lookup"><span data-stu-id="657f5-311">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-314">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-314">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="657f5-315">Access</span><span class="sxs-lookup"><span data-stu-id="657f5-315">Access</span></span>

- <span data-ttu-id="657f5-316">Исправлена проблема, из-за которой приложение неожиданно завершало работу при использовании окна "Масштаб".</span><span class="sxs-lookup"><span data-stu-id="657f5-316">Fixed an issue where the application would  close unexpectedly when using Zoom window.</span></span>


- <span data-ttu-id="657f5-317">Исправлена проблема, из-за которой при попытке выполнить определенные запросы ранее появлялось сообщение об ошибке "Слишком сложный запрос".</span><span class="sxs-lookup"><span data-stu-id="657f5-317">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


- <span data-ttu-id="657f5-318">Это исправление исправляет проблему, из-за которой Access мог аварийно завершать работу при запуске функции Масштаб (Shift + F2) для редактирования текста.</span><span class="sxs-lookup"><span data-stu-id="657f5-318">This change fixes an issue that could cause Access to to close unexpectedly when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="657f5-319">Устранена проблема со вставкой связанных таблиц SQL, содержащих поле удостоверения (например, счетчик).</span><span class="sxs-lookup"><span data-stu-id="657f5-319">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


- <span data-ttu-id="657f5-320">Исправлена проблема, из-за которой выполнение запроса занимало примерно в два раза больше времени, чем ожидалось.</span><span class="sxs-lookup"><span data-stu-id="657f5-320">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


- <span data-ttu-id="657f5-321">Исправлена проблема, препятствующая возможности вызова расширенного типа данных "Дата/время" без сбоев приложения.</span><span class="sxs-lookup"><span data-stu-id="657f5-321">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any issues in your app.</span></span>


- <span data-ttu-id="657f5-322">Проблема исправлена, поэтому теперь вы можете вернуться к последней версии Access и использовать DAO/VBA для управления и изменения типа данных Decimal.</span><span class="sxs-lookup"><span data-stu-id="657f5-322">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>


- <span data-ttu-id="657f5-323">Исправлена ошибка, возникавшая при попытке использовать построитель DSN ODBC</span><span class="sxs-lookup"><span data-stu-id="657f5-323">We fixed an error issue when trying to use ODBC DSN builder</span></span>


- <span data-ttu-id="657f5-324">Эта проблема устранена. Теперь вы можете использовать драйвер ODBC вне приложений Office "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="657f5-324">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="excel"></a><span data-ttu-id="657f5-325">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-325">Excel</span></span>

- <span data-ttu-id="657f5-326">Для рабочих книг, доступных только для чтения, могла действовать автоматическая классификация документов.</span><span class="sxs-lookup"><span data-stu-id="657f5-326">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>


- <span data-ttu-id="657f5-327">Исправлен сбой, который мог происходить при попытке создать подключение к данным, если вы вышли из учетной записи.</span><span class="sxs-lookup"><span data-stu-id="657f5-327">Fixed an issue that could happen when trying to create a data connection if you have signed out from your account.</span></span>


- <span data-ttu-id="657f5-328">Исправлена ошибка с API PivotDateFilter, из-за которой условия фильтрации "До" и "После" менялись местами.</span><span class="sxs-lookup"><span data-stu-id="657f5-328">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="657f5-329">Исправлена проблема, из-за которой приложение Excel аварийно завершало работу при попытке вставки сводных таблиц на лист диаграмм.</span><span class="sxs-lookup"><span data-stu-id="657f5-329">Addressed an issue where Excel may close unexpectedly when attempting to insert PivotTables into a chart sheet.</span></span>


- <span data-ttu-id="657f5-330">Исправлена ошибка, из-за которой не удавалось изменять сводные таблицы и сохранять книги, если они были экспортированы из плана Project.</span><span class="sxs-lookup"><span data-stu-id="657f5-330">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="657f5-331">Могла возникать ошибка при попытке сохранить файл, содержащий формулу с функцией ПУСТЬ().</span><span class="sxs-lookup"><span data-stu-id="657f5-331">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


- <span data-ttu-id="657f5-332">Исправлена ошибка, из-за которой в некоторых случаях при открытии файла в режиме "только для чтения" отображалось несколько панелей сообщений.</span><span class="sxs-lookup"><span data-stu-id="657f5-332">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="657f5-333">Исправлена ошибка, из-за которой происходил сбой работы промежуточных итогов структуры при большом количестве повторяющихся значений заголовков столбцов.</span><span class="sxs-lookup"><span data-stu-id="657f5-333">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="657f5-334">Исправлена проблема, из-за которой при открытии книг только для чтения, было невозможно обновить данные сводной таблицы.</span><span class="sxs-lookup"><span data-stu-id="657f5-334">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="657f5-335">Это изменение позволяет устранить следующие проблемы: при вставке файла из локальной папки синхронизации OneDrive Excel не отображает правильный значок "Вставить объект".</span><span class="sxs-lookup"><span data-stu-id="657f5-335">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="657f5-336">Исправлена ошибка, из-за которой происходил сбой работы Excel при обновлении объекта групповой политики (например, с помощью удаленного обновления групповой политики) во время многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="657f5-336">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="657f5-337">Исправлена ошибка, из-за которой происходил сбой работы Excel при использовании функции промежуточных итогов в более чем 255 столбцах.</span><span class="sxs-lookup"><span data-stu-id="657f5-337">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="657f5-338">Улучшен кернинг текста в PowerPoint при копировании содержимого из Excel и его вставке в PowerPoint с помощью функции внедрения.</span><span class="sxs-lookup"><span data-stu-id="657f5-338">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="657f5-339">Исправлена ошибка, которая блокировала переключение из режима предварительного просмотра таблицы и редактора запросов в PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="657f5-339">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="657f5-340">Исправлена ошибка, из-за которой пользователь не мог напрямую открыть файл atomsvc (UTF8+BOM) в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="657f5-340">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="657f5-341">Исправлена проблема, из-за которой клиенты не получали уведомлений о новой версии файла при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="657f5-341">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="657f5-342">Исправлена проблема с редактированием, из-за которой использование редактора метода ввода в режиме перезаписи приводило к неправильному изменению дополнительных символов.</span><span class="sxs-lookup"><span data-stu-id="657f5-342">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="657f5-343">Исправлена проблема при использовании данных в режиме реального времени в сочетании с функцией многопоточного пересчета.</span><span class="sxs-lookup"><span data-stu-id="657f5-343">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="657f5-344">Исправляет проблему, из-за которой приложение Excel не запускалось или неожиданно завершало работу, если применялись определенные параметры службы "Безопасность Windows" для защиты от эксплойтов (SimExec, CallerCheck)</span><span class="sxs-lookup"><span data-stu-id="657f5-344">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="657f5-345">Исправлена проблема, из-за которой Excel мог аварийно завершать работу в определенных обстоятельствах при использовании форматирования по образцу.</span><span class="sxs-lookup"><span data-stu-id="657f5-345">Fixed an issue where Excel could close unexpectedly in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="657f5-346">Исправлена ошибка, из-за которой пользователи не могли изменить фильтр сводной таблицы, потому что его параметр был настроен на значение, которого больше нет в базе данных Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="657f5-346">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="657f5-347">Исправлена проблема, из-за которой Excel мог аварийно завершать работу при использовании экспресс-анализа после закрепления верхней строки листа.</span><span class="sxs-lookup"><span data-stu-id="657f5-347">Fixed an issue where Excel could close unexpectedly when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="657f5-348">Исправлена проблема, из-за которой некоторые функции выдавали неправильный результат после загрузки книги.</span><span class="sxs-lookup"><span data-stu-id="657f5-348">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="657f5-349">Исправлена проблема с неожиданным завершением работы приложения, которое было связано со ссылками и именованными диапазонами надстройки XLAM.</span><span class="sxs-lookup"><span data-stu-id="657f5-349">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="657f5-350">Исправлена проблема, из-за которой создавались неверные ссылки на ячейки при использовании макроса для настройки свойства FormulaR1C1 для диапазона, если лист диаграммы являлся активным листом.</span><span class="sxs-lookup"><span data-stu-id="657f5-350">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="657f5-351">Исправлена проблема, которая могла вызывать сообщение об ошибке "При попытке вычисления одной или нескольких формул ресурсы Excel закончились".</span><span class="sxs-lookup"><span data-stu-id="657f5-351">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="657f5-352">Исправлена проблема с испанским языком в Office, когда в списках проверки данных могли отображаться не все элементы.</span><span class="sxs-lookup"><span data-stu-id="657f5-352">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="657f5-353">Исправлена проблема, которая могла приводить к зависанию при обновлении сводных таблиц OLAP.</span><span class="sxs-lookup"><span data-stu-id="657f5-353">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="657f5-354">Исправлена проблема, из-за которой удалялась настраиваемая вкладка в CustomUI XML при сохранении в SharePoint или OneDrive.</span><span class="sxs-lookup"><span data-stu-id="657f5-354">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


- <span data-ttu-id="657f5-355">Исправлена проблема, из-за которой приложение Excel иногда переставало отвечать после нажатия клавиш CTRL+SHIFT+клавиши со стрелками для прокрутки, если окно Excel демонстрировалось в Teams.</span><span class="sxs-lookup"><span data-stu-id="657f5-355">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="657f5-356">Исправлена проблема, из-за которой в некоторых случаях при щелчке по гиперссылке внутри книги она перестает отображаться.</span><span class="sxs-lookup"><span data-stu-id="657f5-356">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


- <span data-ttu-id="657f5-357">Application.Evaluate (VBA) не работал для пользовательских функций в некоторых случаях.</span><span class="sxs-lookup"><span data-stu-id="657f5-357">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>


- <span data-ttu-id="657f5-358">Для книг, сохраненных с цифровой подписью в Excel 2016, подпись может быть признана недействительной при открытии в текущей версии Excel.</span><span class="sxs-lookup"><span data-stu-id="657f5-358">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


- <span data-ttu-id="657f5-359">Исправлена ошибка, из-за которой в некоторых случаях происходил сбой Excel после копирования листа, содержащего сводную таблицу.</span><span class="sxs-lookup"><span data-stu-id="657f5-359">Fixed an issue which would cause Excel to close unexpectedly in some cases after copying a sheet containing a PivotTable.</span></span>


- <span data-ttu-id="657f5-360">Исправлена проблема, из-за которой внешняя ссылка не срабатывала при повторном открытии файла, если путь к файлу был слишком длинным.</span><span class="sxs-lookup"><span data-stu-id="657f5-360">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


- <span data-ttu-id="657f5-361">Исправлена проблема, из-за которой использование данных в реальном времени в сочетании с функцией многопоточного пересчета могло привести к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="657f5-361">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="657f5-362">Устранена проблема, из-за которой внешние ссылки не обновлялись при заполнении, если исходная книга закрыта.</span><span class="sxs-lookup"><span data-stu-id="657f5-362">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


- <span data-ttu-id="657f5-363">Исправлена проблема, которая могла вызывать предупреждение о поврежденной книге, если она содержала формулы с ЕСНД().</span><span class="sxs-lookup"><span data-stu-id="657f5-363">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="657f5-364">Исправлена ошибка, из-за которой Power Pivot не мог распознавать разделитель вкладок.</span><span class="sxs-lookup"><span data-stu-id="657f5-364">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="onenote"></a><span data-ttu-id="657f5-365">OneNote</span><span class="sxs-lookup"><span data-stu-id="657f5-365">OneNote</span></span>

- <span data-ttu-id="657f5-366">Информирование пользователей с помощью информационной панели о временных изменениях в Microsoft OneNote, помогающих улучшить синхронизацию и доступность служб при высоком уровне использования по всему миру.</span><span class="sxs-lookup"><span data-stu-id="657f5-366">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


- <span data-ttu-id="657f5-367">Улучшена синхронизация и стабильность службы путем временного изменения частоты синхронизации в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="657f5-367">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="657f5-368">Улучшено обнаружение состояния совместного редактирования для снижения использования ресурсов</span><span class="sxs-lookup"><span data-stu-id="657f5-368">Improved detection of co-authoring status to reduce resource utilization.</span></span>


- <span data-ttu-id="657f5-369">Улучшена синхронизация и стабильность службы за счет временного изменения частоты создания журналов версий страниц.</span><span class="sxs-lookup"><span data-stu-id="657f5-369">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="657f5-370">Улучшена синхронизация и стабильность службы путем временного уменьшения максимально допустимого размера новых внедренных вложений до 50 МБ в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="657f5-370">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="657f5-371">В случае файлов большего размера у пользователей будет возможность отправить файл в OneDrive и вставить ссылку в OneNote.</span><span class="sxs-lookup"><span data-stu-id="657f5-371">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="657f5-372">Улучшена синхронизация и стабильность службы путем временного отключения записи видео в приложении в OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="657f5-372">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="657f5-373">Это мера не влияет на локальные записные книжки.</span><span class="sxs-lookup"><span data-stu-id="657f5-373">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="657f5-374">Улучшена синхронизация и стабильность службы за счет временного отключения перемещения страниц в корзину.</span><span class="sxs-lookup"><span data-stu-id="657f5-374">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="657f5-375">Для пользователей, которым нужно удалить страницу, будет отображаться диалоговое окно с вопросом, нужно ли удалить страницу окончательно.</span><span class="sxs-lookup"><span data-stu-id="657f5-375">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="657f5-376">Была исправлена проблема, из-за которой не загружалось меню проверки орфографии.</span><span class="sxs-lookup"><span data-stu-id="657f5-376">We fixed an issue where the spelling menu was not loading.</span></span>


### <a name="outlook"></a><span data-ttu-id="657f5-377">Outlook</span><span class="sxs-lookup"><span data-stu-id="657f5-377">Outlook</span></span>

- <span data-ttu-id="657f5-378">Исправлена проблема, из-за которой необязательные сетевые функции блокировали загрузку веб-надстроек.</span><span class="sxs-lookup"><span data-stu-id="657f5-378">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <span data-ttu-id="657f5-379">Подробнее об этом см. здесь: https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span><span class="sxs-lookup"><span data-stu-id="657f5-379">See more detail here:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span></span>


- <span data-ttu-id="657f5-380">Исправлена проблема, из-за которой пользователи теперь могут отключить службу IRM (управление правами на доступ к данным) для Outlook, не отключая ее для других приложений Office.</span><span class="sxs-lookup"><span data-stu-id="657f5-380">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="657f5-381">Исправлена ошибка, из-за которой пользователи не могли предоставить разрешение "Редактор" своим делегатам.</span><span class="sxs-lookup"><span data-stu-id="657f5-381">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="657f5-382">Исправлена ошибка, из-за которой неожиданно завершалась работа приложения при выделении пользователем результата поиска.</span><span class="sxs-lookup"><span data-stu-id="657f5-382">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="657f5-383">Исправлена проблема, из-за которой пользователи, пытавшиеся создать приглашение на собрание из дополнительной учетной записи, добавленной в их профиль, не видели пустое поле "От:" вместо своего адреса.</span><span class="sxs-lookup"><span data-stu-id="657f5-383">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


- <span data-ttu-id="657f5-384">Исправлена проблема, из-за которой пользователи не могли подключаться к общедоступным папкам после добавления общего почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="657f5-384">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="657f5-385">Устранена проблема, из-за которой в некоторых обстоятельствах не удавалось удалять отклоненные представителем собрания из календаря руководителя.</span><span class="sxs-lookup"><span data-stu-id="657f5-385">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="657f5-386">Исправлена проблема, не позволявшая некоторым пользователям функции улучшений общего календаря просматривать недавно добавленный общий календарь.</span><span class="sxs-lookup"><span data-stu-id="657f5-386">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="657f5-387">Исправлена проблема, из-за которой пользователи не могли закрыть общие календари, щелкнув значок "X" в углу.</span><span class="sxs-lookup"><span data-stu-id="657f5-387">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="657f5-388">Исправлена проблема, из-за которой иногда не удавалось применить параметр "Включить улучшения общего календаря" к существующим общим календарям.</span><span class="sxs-lookup"><span data-stu-id="657f5-388">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="657f5-389">Исправлена проблема, из-за которой поисковые запросы в календарях групп не возвращали никаких результатов.</span><span class="sxs-lookup"><span data-stu-id="657f5-389">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="657f5-390">Исправлена проблема, из-за которой возникало случайное закрытие при взаимодействии пользователей с облачными вложениями.</span><span class="sxs-lookup"><span data-stu-id="657f5-390">Fixes an issue that caused users to experience occasional closures when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="657f5-391">Устранена проблема, из-за которой пользователи CLP могут столкнуться с закрытием при замене контекста адреса отправителя ответа с защищенного на незащищенный.</span><span class="sxs-lookup"><span data-stu-id="657f5-391">Addressed an issue that caused users of CLP to experience an issue when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="657f5-392">Исправлена проблема, из-за которой при открытии облачного вложения ошибка отображалась на странице безопасных ссылок, а не в открываемом документе.</span><span class="sxs-lookup"><span data-stu-id="657f5-392">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="657f5-393">Исправлена проблема, из-за которой Outlook не удавалось включать советы по политике защиты от потери данных для пользователей, которые приобрели подписку на Microsoft 365 бизнес премиум.</span><span class="sxs-lookup"><span data-stu-id="657f5-393">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="657f5-394">Исправлена проблема, связанная с событием аудита CLP для метки "Ответить или переслать".</span><span class="sxs-lookup"><span data-stu-id="657f5-394">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="657f5-395">Устранена проблема, которая приводила к неожиданному изменению ширины области папок.</span><span class="sxs-lookup"><span data-stu-id="657f5-395">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="657f5-396">Исправлена ошибка, из-за которой поле "Кому" было пустым при отправке отчета о состоянии задачи.</span><span class="sxs-lookup"><span data-stu-id="657f5-396">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="657f5-397">Исправлена ошибка, из-за которой происходил сбой события MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="657f5-397">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="657f5-398">Устранена проблема, из-за которой дата создания вложений, скопированных в свою файловую систему с помощью перетаскивания, отображалась для пользователей как 1 января 4501 г.</span><span class="sxs-lookup"><span data-stu-id="657f5-398">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>


- <span data-ttu-id="657f5-399">Устранена проблема, из-за которой при добавлении интеллектуальной ссылки в файл SharePoint имена файлов неправильно отображались для пользователей некоторых наборов символов.</span><span class="sxs-lookup"><span data-stu-id="657f5-399">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="657f5-400">Исправлена проблема, из-за которой при обновлении правил в Outlook появлялось сообщение "Правила на этом компьютере не соответствуют правилам Microsoft Exchange".</span><span class="sxs-lookup"><span data-stu-id="657f5-400">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="657f5-401">Устранена проблема, из-за которой Outlook не удавалось получить варианты поиска.</span><span class="sxs-lookup"><span data-stu-id="657f5-401">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="657f5-402">Устранена проблема, из-за которой пользователи общего календаря сталкивались со сбоями в календаре.</span><span class="sxs-lookup"><span data-stu-id="657f5-402">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="657f5-403">Устранена проблема, которая в некоторых ситуациях приводила к периодическим зависаниям и сбоям.</span><span class="sxs-lookup"><span data-stu-id="657f5-403">Addressed an issue that caused users to experience intermittent hangs and closures in some scenarios.</span></span>


- <span data-ttu-id="657f5-404">Устранена проблема, при которой удаление 4 и более сообщений электронной почты из учетной записи POP с выбранным параметром "Скачивать только заголовки" вызывало сбой.</span><span class="sxs-lookup"><span data-stu-id="657f5-404">Addressed an issue which caused users to experience an issue when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="657f5-405">Исправлена проблема, из-за которой у делегатов возникали периодические сбои при открытии общих папок в другом почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="657f5-405">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="657f5-406">Исправлена проблема, из-за которой некоторые автоматически созданные сообщения электронной почты отправлялись пустыми, если строка темы была пустой.</span><span class="sxs-lookup"><span data-stu-id="657f5-406">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="657f5-407">Исправлена проблема с отсутствием параметра "Разрешить переадресацию" в разделе "Параметры ответа" в собрании общего календаря, если НЕ установлен флажок скачивания общей папки.</span><span class="sxs-lookup"><span data-stu-id="657f5-407">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="657f5-408">Исправлена проблема, из-за которой у представителей при редактировании существующей встречи в календаре руководителя отображалось сообщение об ошибке.</span><span class="sxs-lookup"><span data-stu-id="657f5-408">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="657f5-409">Устранена проблема, из-за которой у пользователей возникали сбои в сторонних приложениях MAPI.</span><span class="sxs-lookup"><span data-stu-id="657f5-409">Addressed an issue that caused users to experience an issue in third party MAPI applications.</span></span>


- <span data-ttu-id="657f5-410">Исправлена проблема, приводившая к неожиданному закрытию Outlook при открытии файлов MSG или OFT, сохраненных локально, после обновления Windows.</span><span class="sxs-lookup"><span data-stu-id="657f5-410">Addressed an issue that caused Outlook to close unexpectedly when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="657f5-411">Устранена проблема, приводившая к неожиданному закрытию Outlook в некоторых сборках Windows.</span><span class="sxs-lookup"><span data-stu-id="657f5-411">Addressed an issue that caused Outlook to close unexpectedly on some builds of Windows.</span></span>


- <span data-ttu-id="657f5-412">Устранена проблема, которая приводила к выводу предупреждений о недопустимом состоянии антивирусной программы в Windows 10 Server.</span><span class="sxs-lookup"><span data-stu-id="657f5-412">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="657f5-413">Эта версия Windows поддерживает обнаружение вирусов, но антивирусные программы не найдены, несмотря на то, что антивирусная программа установлена.</span><span class="sxs-lookup"><span data-stu-id="657f5-413">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>


- <span data-ttu-id="657f5-414">Исправлена ошибка, из-за которой приложение неожиданно закрывалось при отправке почты Outlook из других приложений.</span><span class="sxs-lookup"><span data-stu-id="657f5-414">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="657f5-415">Исправлена проблема с производительностью при отправке вложений.</span><span class="sxs-lookup"><span data-stu-id="657f5-415">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="657f5-416">Устранена проблема, из-за которой пользователи получали предложение запустить средство восстановление папки "Входящие".</span><span class="sxs-lookup"><span data-stu-id="657f5-416">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="657f5-417">Устранена проблема, из-за которой иногда происходило неожиданное закрытие при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="657f5-417">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="657f5-418">Устранена проблема, связанная с тем, что пользователи не могли сохранять вложения OneDrive вне клиента на локальный компьютер при сохранении через диалоговое окно "Безопасность".</span><span class="sxs-lookup"><span data-stu-id="657f5-418">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="657f5-419">Исправлена ошибка, из-за которой заголовки сообщений на китайском языке искажались при ответе или пересылке.</span><span class="sxs-lookup"><span data-stu-id="657f5-419">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="657f5-420">Решена проблема, из-за которой страница помощника по планированию не отображается.</span><span class="sxs-lookup"><span data-stu-id="657f5-420">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="657f5-421">Устранена проблема, из-за которой страница помощника по планированию не отображалась для некоторых пользователей.</span><span class="sxs-lookup"><span data-stu-id="657f5-421">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="657f5-422">Исправлена ошибка, из-за которой снижалась производительность при перемещении нескольких почтовых элементов между папками в интерактивном режиме.</span><span class="sxs-lookup"><span data-stu-id="657f5-422">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="657f5-423">Добавлен раздел реестра, позволяющий пользователям отключить добавление параметра filetime для вложений в операциях IDataObject (т. е. перетаскивание, буфер обмена).</span><span class="sxs-lookup"><span data-stu-id="657f5-423">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="657f5-424">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = параметры filetime исключены 1 = (по умолчанию) параметры filetime включены</span><span class="sxs-lookup"><span data-stu-id="657f5-424">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="657f5-425">Исправлена ошибка, из-за которой исчезали встроенные изображения при ответе на сообщение с меткой защиты от Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="657f5-425">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="657f5-426">Исправлена ошибка, из-за которой имя пользователя отображалось как номер телефона при отправке голосовых сообщений, защищенных службой Azure, в результате чего пользователи классического приложения Outlook не могли открывать голосовые сообщения от внешних пользователей.</span><span class="sxs-lookup"><span data-stu-id="657f5-426">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="657f5-427">Исправлена ошибка, из-за которой при настройке конфигурации OME добавлялись лишние вложения в элемент электронной почты, в результате чего Outlook шифровал сообщение, даже если на стороне службы был настроен параметр DecryptAttachmentsForEncryptOnly.</span><span class="sxs-lookup"><span data-stu-id="657f5-427">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


- <span data-ttu-id="657f5-428">Исправлена проблема, из-за которой параметры "Только шифрование" и "Не пересылать" оставались включенными в некоторых сценариях, несмотря на то, что они были отключены политикой.</span><span class="sxs-lookup"><span data-stu-id="657f5-428">We fixed an issue that caused the Encrypt Only and Do Not Forward options to continue to be enabled in some scenarios despite being disabled by policy.</span></span>


- <span data-ttu-id="657f5-429">Устранена проблема, из-за которой терялось форматирование SmartLinks при сохранении в черновиках.</span><span class="sxs-lookup"><span data-stu-id="657f5-429">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="657f5-430">Исправлена проблема, из-за которой пользователь не мог настроить текст обоснования при переопределении политики.</span><span class="sxs-lookup"><span data-stu-id="657f5-430">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="657f5-431">Исправлена проблема, из-за которой китайские иероглифы заменялись на знаки вопроса при сохранении в виде файла OFT.</span><span class="sxs-lookup"><span data-stu-id="657f5-431">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="657f5-432">Устранена проблема, которая иногда приводила к неожиданному завершению работы при получении сведений о пользователе.</span><span class="sxs-lookup"><span data-stu-id="657f5-432">Addressed an issue that caused users to occasionally experience unexpected closures when retrieving persona information.</span></span>


- <span data-ttu-id="657f5-433">Исправлена проблема, из-за которой происходило неожиданное завершение работы при изменении получателей пользователями.</span><span class="sxs-lookup"><span data-stu-id="657f5-433">This fixes an issue that caused users to experience occasional application closures when editing recipients.</span></span>


- <span data-ttu-id="657f5-434">Исправлена проблема, из-за которой возникали аномалии при использовании пользователями компактного представления.</span><span class="sxs-lookup"><span data-stu-id="657f5-434">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="657f5-435">Устранена проблема, из-за которой у пользователей Outlook возникали проблемы с навигацией в компактных представлениях.</span><span class="sxs-lookup"><span data-stu-id="657f5-435">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="657f5-436">Устранена проблема, из-за которой контекстное меню, вызываемое щелчком правой кнопки мыши, не отображалось в элементах управления поиском.</span><span class="sxs-lookup"><span data-stu-id="657f5-436">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="657f5-437">Исправлена проблема, из-за которой пользователи получали следующую ошибку при ответе или создании сообщения: "Часть файлов с этой веб-страницы отсутствует в указанных папках.</span><span class="sxs-lookup"><span data-stu-id="657f5-437">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="657f5-438">Вы все равно хотите скачать их?</span><span class="sxs-lookup"><span data-stu-id="657f5-438">Do you want to download them anyway?</span></span> <span data-ttu-id="657f5-439">Если вы уверены в надежности источника веб-страницы, выберите "Да".</span><span class="sxs-lookup"><span data-stu-id="657f5-439">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="657f5-440">Устранена проблема, из-за которой пользователи сталкивались с зависанием интерфейса при выходе из Outlook.</span><span class="sxs-lookup"><span data-stu-id="657f5-440">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


- <span data-ttu-id="657f5-441">Устранена проблема, из-за которой поиск возможности предложения функции не возвращал результатов, и пользователи не могли делиться идеями.</span><span class="sxs-lookup"><span data-stu-id="657f5-441">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


- <span data-ttu-id="657f5-442">Устранена проблема, вызывающая нарушения в форматировании оповещений об инцидентах.</span><span class="sxs-lookup"><span data-stu-id="657f5-442">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="657f5-443">Устранена проблема, из-за которой у пользователей происходило неожиданное завершение работы при отправлении отзывов из уведомлений администратора.</span><span class="sxs-lookup"><span data-stu-id="657f5-443">Addressed an issue that caused users to experience sudden closures when submitting feedback from an Admin Notification.</span></span>


- <span data-ttu-id="657f5-444">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="657f5-444">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="657f5-445">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="657f5-445">PowerPoint</span></span>

- <span data-ttu-id="657f5-446">Это изменение исправляет проблему, связанную с функцией экспорта в GIF с анимацией, когда не выполнялся экспорт при нажатии кнопки "Экспорт".</span><span class="sxs-lookup"><span data-stu-id="657f5-446">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="657f5-447">Исправлена ошибка, из-за которой содержимое надстройки Forms не отображалось после вставки, пока пользователь не щелкал другой слайд для отображения.</span><span class="sxs-lookup"><span data-stu-id="657f5-447">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


- <span data-ttu-id="657f5-448">Исправление системы безопасности для решения проблемы, связанной с отключением защиты IRM при открытии файла PowerPoint в режиме защищенного просмотра.</span><span class="sxs-lookup"><span data-stu-id="657f5-448">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="657f5-449">Исправлена проблема VBA, приводившая к неожиданному завершению работы Slide.Shapes.AddMediaObject2 при использовании устаревших форматов видео (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="657f5-449">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="657f5-450">Исправлена проблема, из-за которой связанная диаграмма Excel неправильно менялась на листе Excel при изменении исходного пути к локальной папке OneDrive.</span><span class="sxs-lookup"><span data-stu-id="657f5-450">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="657f5-451">Устранена проблема, из-за которой обновлялись примечания в случае, когда в файлах были примечания одновременно из старых и новых версий.</span><span class="sxs-lookup"><span data-stu-id="657f5-451">Fixed an issue when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


- <span data-ttu-id="657f5-452">Исправлена проблема с панелью предложений, которая могла вызвать неожиданное завершение работы приложения.</span><span class="sxs-lookup"><span data-stu-id="657f5-452">We have fixed an issue with suggestion pane that may cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="657f5-453">Исправлена проблема в диалоговом окне "Параметры действия", которая приводила к неожиданному завершению работы приложении PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="657f5-453">We have fixed an issue in Action Settings dialog which was causing the PowerPoint app to close unexpectedly.</span></span>


- <span data-ttu-id="657f5-454">Исправлена проблема с приложением PowerPoint, которая приводила к неожиданному завершению работы.</span><span class="sxs-lookup"><span data-stu-id="657f5-454">We have fixed an issue with PowerPoint app that may cause it to close unexpectedly.</span></span>


- <span data-ttu-id="657f5-455">Исправлена ошибка, из-за которой функция "Рады видеть вас снова!</span><span class="sxs-lookup"><span data-stu-id="657f5-455">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="657f5-456">Продолжайте работу в Office с того места, на котором остановились" не работала в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="657f5-456">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


- <span data-ttu-id="657f5-457">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="657f5-457">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="657f5-458">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="657f5-458">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="657f5-459">Исправлена проблема, из-за которой слайд-шоу в режиме защищенного просмотра не работало.</span><span class="sxs-lookup"><span data-stu-id="657f5-459">We fixed an issue where Slideshow in protected view was not working.</span></span>


### <a name="project"></a><span data-ttu-id="657f5-460">Project</span><span class="sxs-lookup"><span data-stu-id="657f5-460">Project</span></span>

- <span data-ttu-id="657f5-461">Исправлена проблема, из-за которой задача, выбранная в диалоговом окне "Назначение ресурсов", не совпадала с задачей, выбранной на "Доске задач".</span><span class="sxs-lookup"><span data-stu-id="657f5-461">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="657f5-462">Исправлена проблема, из-за которой при определении для ресурса нескольких таблиц норм затрат оставшиеся затраты не всегда рассчитывались правильно.</span><span class="sxs-lookup"><span data-stu-id="657f5-462">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


- <span data-ttu-id="657f5-463">Исправлена проблема, из-за которой дата окончания проекта не обновлялась для проектов, подключенных к списку задач SharePoint.</span><span class="sxs-lookup"><span data-stu-id="657f5-463">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="657f5-464">Исправлена проблема, из-за которой при использовании Project, подключенного к Project Web App, метод добавления TaskDependencies завершался сбоем при попытке добавления задержки к зависимости.</span><span class="sxs-lookup"><span data-stu-id="657f5-464">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


- <span data-ttu-id="657f5-465">Исправлена проблема, из-за которой процент выполнения задачи неправильно изменялся на значение менее 100 % после ее пометки как выполненной.</span><span class="sxs-lookup"><span data-stu-id="657f5-465">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="657f5-466">Исправлена проблема, из-за которой событие OnUndoOrRedo не запускалось без предварительного выполнения метода OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="657f5-466">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="657f5-467">Исправлена проблема, из-за которой иногда неверно вычислялись даты суммарной задачи.</span><span class="sxs-lookup"><span data-stu-id="657f5-467">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="657f5-468">Исправлена проблема, из-за которой событие ProjectBeforeTaskChange не обнаруживает, деактивирована или активирована ли задача при помощи кнопки "Деактивировать".</span><span class="sxs-lookup"><span data-stu-id="657f5-468">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="657f5-469">Устранена проблема, из-за которой при редактировании данных Предшественника или Преемника в представлении формы, запускалось дополнительное событие ProjectBeforeTaskChange.</span><span class="sxs-lookup"><span data-stu-id="657f5-469">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="657f5-470">Исправлена проблема, из-за которой приложение Project могло аварийно завершать работу при сохранении проектов, созданных в предыдущих версиях Project.</span><span class="sxs-lookup"><span data-stu-id="657f5-470">Fixed an issue where Project may close unexpectedly when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="657f5-471">Исправлена проблема, из-за которой пользователю не удавалось ввести повременные базовые трудозатраты, если был включен параметр защиты фактических трудозатрат.</span><span class="sxs-lookup"><span data-stu-id="657f5-471">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="657f5-472">Исправлена проблема, из-за которой не удавалось сохранить файл PDF или XPS из Project в библиотеке документов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="657f5-472">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="657f5-473">Исправлена проблема, из-за которой при вставке задачи, имеющей несколько зависимостей, не все зависимости были скопированы правильно.</span><span class="sxs-lookup"><span data-stu-id="657f5-473">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="657f5-474">Устранена проблема, из-за которой проекты не открывались в классическом клиенте Project из Project Web App, если URL-адрес оканчивался на ".com".</span><span class="sxs-lookup"><span data-stu-id="657f5-474">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="657f5-475">Устранена проблема, из-за которой событие ProjectBeforeTaskChange не запускалось при наличии изменений в суммарной задаче проекта, либо в поле даты начала, либо задачи.</span><span class="sxs-lookup"><span data-stu-id="657f5-475">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="657f5-476">Исправлена проблема, из-за которой прогресс задачи, помеченной как завершенная на 100%, некорректно изменяется в меньшую сторону.</span><span class="sxs-lookup"><span data-stu-id="657f5-476">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


- <span data-ttu-id="657f5-477">Исправлена проблема, из-за которой Project мог неожиданно завершать работу при открытии файлов, в которых контуры ресурсов были указаны определенным образом.</span><span class="sxs-lookup"><span data-stu-id="657f5-477">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="657f5-478">Skype</span><span class="sxs-lookup"><span data-stu-id="657f5-478">Skype</span></span>

- <span data-ttu-id="657f5-479">Цвет кожи танцующего смайлика изменен на нейтральный.</span><span class="sxs-lookup"><span data-stu-id="657f5-479">Changed dancing emoticon skin tone to neutral color.</span></span>


- <span data-ttu-id="657f5-480">Если пользователю назначена политика, которая перемещает его только в Teams, он все еще может использовать надстройку Outlook для Skype для бизнеса для планирования собраний.</span><span class="sxs-lookup"><span data-stu-id="657f5-480">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="657f5-481">После этого обновления вы больше не сможете планировать собрания Skype для бизнеса, если клиент запустит политику, указывающую на то, что у пользователя есть возможность использовать только Teams, а собрания станут доступны только в режиме присоединения.</span><span class="sxs-lookup"><span data-stu-id="657f5-481">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="657f5-482">Кроме того, надстройка Outlook для Skype для бизнеса перестанет активироваться при запуске, если клиент Skype для бизнеса доступен только в режиме присоединения к собранию.</span><span class="sxs-lookup"><span data-stu-id="657f5-482">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>


- <span data-ttu-id="657f5-483">Устраняет проблему, из-за которой сертификат TLS-DSK пользователя обновлялся не в ожидаемое время, а только тогда, когда срок его действия оставался менее 12 часов.</span><span class="sxs-lookup"><span data-stu-id="657f5-483">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="657f5-484">Устраняет проблему, при которой пользовательский интерфейс Skype для бизнеса отображается как пустой после входа в систему, когда Office еще не лицензирован.</span><span class="sxs-lookup"><span data-stu-id="657f5-484">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="visio"></a><span data-ttu-id="657f5-485">Visio</span><span class="sxs-lookup"><span data-stu-id="657f5-485">Visio</span></span>

- <span data-ttu-id="657f5-486">Исправлена проблема, которая приводила к неожиданному завершению работы в режиме динамического просмотра при выравнивании текста.</span><span class="sxs-lookup"><span data-stu-id="657f5-486">We fixed an issue that caused the Live preview to close unexpectedly on text alignment.</span></span>


- <span data-ttu-id="657f5-487">Исправлена ошибка, из-за которой пользователи Visio для Office 365 не могли создавать прямые линии с помощью соединительных линий для наборов элементов Visio и встроенных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="657f5-487">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="657f5-488">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-488">Word</span></span>

- <span data-ttu-id="657f5-489">Решена проблема с открытием документов Word из ASPX при наличии в URL-адресе компонента запроса.</span><span class="sxs-lookup"><span data-stu-id="657f5-489">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>


- <span data-ttu-id="657f5-490">Это исправление устраняет проблему, из-за которой приложения Office могли зависнуть в состоянии автоматического сохранения после предыдущего сеанса совместного редактирования.</span><span class="sxs-lookup"><span data-stu-id="657f5-490">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


- <span data-ttu-id="657f5-491">Устранена проблема, которая приводила к неожиданному завершению работы у пользователя при ответе или создании сообщения.</span><span class="sxs-lookup"><span data-stu-id="657f5-491">Addresses an issue that caused users to experience an issue when replying to or composing new email.</span></span>


- <span data-ttu-id="657f5-492">Устранена проблема, из-за которой иногда происходило неожиданное закрытие при использовании кнопки "X" на мыши.</span><span class="sxs-lookup"><span data-stu-id="657f5-492">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="657f5-493">Исправлена проблема, которая приводила к неожиданному завершению работы при открытии некоторых очень больших сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="657f5-493">Fixes an issue that caused users to experience an issue when opening certain very large emails.</span></span>


- <span data-ttu-id="657f5-494">Исправлена проблема, из-за которой при вставке пронумерованных заголовков появлялся дополнительный отступ.</span><span class="sxs-lookup"><span data-stu-id="657f5-494">We fixed an issue where pasted numbered headings showed an additional indent.</span></span>


- <span data-ttu-id="657f5-495">Устранена проблема при копировании и вставке SVG-изображения.</span><span class="sxs-lookup"><span data-stu-id="657f5-495">We fixed an issue for copy and paste SVG image.</span></span>


- <span data-ttu-id="657f5-496">Устранена проблема, из-за которой пользователь мог потерять контент при изменении размера фигуры.</span><span class="sxs-lookup"><span data-stu-id="657f5-496">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="657f5-497">Исправлена проблема, которая приводила к неожиданному завершению работы при открытии документа.</span><span class="sxs-lookup"><span data-stu-id="657f5-497">We fixed an issue which user might experience issues when opening a document.</span></span>


- <span data-ttu-id="657f5-498">Исправлена проблема, из-за которой длинные ссылки не сворачивались при сохранении документа в формате HTML.</span><span class="sxs-lookup"><span data-stu-id="657f5-498">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="657f5-499">Исправлена проблема, из-за которой базовые стили не обновлялись со стилем "Обычный".</span><span class="sxs-lookup"><span data-stu-id="657f5-499">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="657f5-500">Исправлена ошибка с расширениями комментариев, когда ответ на комментарий имел такое же расширение, что и родительский комментарий.</span><span class="sxs-lookup"><span data-stu-id="657f5-500">FIxes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


- <span data-ttu-id="657f5-501">Исправлена ошибка, из-за которой при ответе на родительский комментарий с неизвестным расширением в списке расширений ответ получал то же расширение.</span><span class="sxs-lookup"><span data-stu-id="657f5-501">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="657f5-502">Решена проблема, из-за которой приложение могло неожиданно закрываться при загрузке.</span><span class="sxs-lookup"><span data-stu-id="657f5-502">Resolved an issue that may have caused the application to close unexpectedly when booting.</span></span>


- <span data-ttu-id="657f5-503">Исправлена проблема с атрибутом сообщения "Не пересылать" в Outlook.</span><span class="sxs-lookup"><span data-stu-id="657f5-503">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="657f5-504">Исправлена проблема с диалоговым окном "Коллекция стилей".</span><span class="sxs-lookup"><span data-stu-id="657f5-504">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="657f5-505">Исправлена проблема, из-за которой макрос AutoOpen запускается до AutoExec</span><span class="sxs-lookup"><span data-stu-id="657f5-505">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


### <a name="office-suite"></a><span data-ttu-id="657f5-506">Набор Office</span><span class="sxs-lookup"><span data-stu-id="657f5-506">Office Suite</span></span>

- <span data-ttu-id="657f5-507">Исправлена проблема для старой области общего доступа, не основанной на веб-службе, из-за которой при закрытии документа при открытой области общего доступа приложение могло неожиданно закрыться.</span><span class="sxs-lookup"><span data-stu-id="657f5-507">Fixed an issue for the old, non-web service based Share pane, where upon closing the document while the Share pane is open could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="657f5-508">Исправлена проблема с синхронизацией, из-за которой приложение могло неожиданно завершать работу при закрытии файлов office.</span><span class="sxs-lookup"><span data-stu-id="657f5-508">Fixed a timing issue that could cause the application to close unexpectedly when closing office files.</span></span>


- <span data-ttu-id="657f5-509">Устранена проблема, из-за которой пользователи не могли импортировать списки SPO при отключенной ADAL.</span><span class="sxs-lookup"><span data-stu-id="657f5-509">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>


- <span data-ttu-id="657f5-p135">Когда пользователь печатает документ или файл на струйных принтерах Office и в картридже принтера заканчиваются чернила, появляется сообщение "Мало тонера" или "Нет тонера", несмотря на то, что в струйных принтерах тонера нет в принципе. Сообщение было изменено и теперь гласит: "Мало чернил или тонера" и "Нет чернил или тонера".</span><span class="sxs-lookup"><span data-stu-id="657f5-p135">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="657f5-512">Мы решили проблему с частотой сбоев ValidateInstall, установив для проверки установки надстройки Bing значение true по умолчанию и приняв успешное возвращение MSI как успешную установку.</span><span class="sxs-lookup"><span data-stu-id="657f5-512">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>


- <span data-ttu-id="657f5-513">Мы отправили новую версию AppV51 на доработку, чтобы исправить ошибки в предыдущей версии AppV51.</span><span class="sxs-lookup"><span data-stu-id="657f5-513">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>


- <span data-ttu-id="657f5-514">Исправлена проблема технологии "Нажми и работай", из-за которой происходил сбой обновления при попытке жесткой связи символьных ссылок.</span><span class="sxs-lookup"><span data-stu-id="657f5-514">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>


- <span data-ttu-id="657f5-515">Исправлена проблема для коммерческих пользователей, применяющих System Center Configuration Manager или другие средства управления для обновления Office с использованием защиты от потери данных в конечной точке Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="657f5-515">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


- <span data-ttu-id="657f5-516">Исправлена проблема, из-за которой сообщение о процессе выполнения появлялось, даже если переход на полную версию продукта завершен.</span><span class="sxs-lookup"><span data-stu-id="657f5-516">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="657f5-517">Чтобы устранить эту проблему, необходимо, чтобы служба правильно производила вычисления, связанные с добавленными продуктами.</span><span class="sxs-lookup"><span data-stu-id="657f5-517">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="657f5-518">Недавно добавленные продукты были отфильтрованы (чтобы убедиться в том, что они существуют в новой конфигурации) и добавлены после существующих идентификаторов выпуска продукта.</span><span class="sxs-lookup"><span data-stu-id="657f5-518">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="657f5-519">Исправлена проблема, из-за которой пользователи видели элементы или содержимое пользовательского интерфейса, которое не отображается при определенных условиях. В частности, при входе или выходе из режима докладчика и использовании нескольких мониторов.</span><span class="sxs-lookup"><span data-stu-id="657f5-519">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="657f5-520">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="657f5-520">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="657f5-521">Это изменение решает проблему с резервным прокси-сервером SVG, в результате которого возникает нарушение прав доступа.</span><span class="sxs-lookup"><span data-stu-id="657f5-521">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>


- <span data-ttu-id="657f5-522">Исправлена высокая загрузка ЦП при простое с использованием GIF или анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="657f5-522">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="657f5-523">Это изменение устраняет потенциальные зависания при загрузке и воспроизведении анимированных данных, таких как GIF или трехмерные модели.</span><span class="sxs-lookup"><span data-stu-id="657f5-523">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>


- <span data-ttu-id="657f5-524">Это изменение решает проблему при запуске приложений Office из-за невозможности загрузки d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="657f5-524">This change addresses a issue when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="657f5-p137">Узел Office неожиданно завершал работу с ошибкой при активации надстройки, если раздел реестра HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth имел значение "0". Внесено изменение, устранившее проблему.</span><span class="sxs-lookup"><span data-stu-id="657f5-p137">The office host was  close unexpectedly in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>


- <span data-ttu-id="657f5-527">Исправлена проблема с неработающим API сообщений для надстроек Office.</span><span class="sxs-lookup"><span data-stu-id="657f5-527">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>

- <span data-ttu-id="657f5-528">Это обновление устраняет проблему в Visual Basic для приложений в Microsoft Office, когда некоторые проекты VBA, содержащие ссылки на библиотеки кода с символами DBCS в имени или пути к библиотеке, будут рассматриваться приложением Office как поврежденные при загрузке.</span><span class="sxs-lookup"><span data-stu-id="657f5-528">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


- <span data-ttu-id="657f5-529">Это обновление устраняет проблему в Microsoft Office, из-за которой проекты Visual Basic для приложений с ссылками, которые должны быть найдены при поиске расположений, указанных в переменной среды PATH, могут быть не найдены в среде выполнения, что приводит к ошибкам среды выполнения VBA.</span><span class="sxs-lookup"><span data-stu-id="657f5-529">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="657f5-530">Это исправление устраняет возникающую ошибку, одновременно блокирующую ограничение доступа и защиту файлов с паролем.</span><span class="sxs-lookup"><span data-stu-id="657f5-530">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="657f5-531">Устранена проблема, которая могла приводить к неожиданному завершению работу при перетаскивании части содержимого из приложения.</span><span class="sxs-lookup"><span data-stu-id="657f5-531">Resolved an issue that may have caused an unexpected closure when dragging some content from the app.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2002-january-12"></a><span data-ttu-id="657f5-533">Версия 2002: 12 января</span><span class="sxs-lookup"><span data-stu-id="657f5-533">Version 2002: January 12</span></span>
<span data-ttu-id="657f5-534">*Версия 2002 (сборка 12527.21504)*</span><span class="sxs-lookup"><span data-stu-id="657f5-534">*Version 2002 (Build 12527.21504)*</span></span>

<span data-ttu-id="657f5-535">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-535">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-537">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-537">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="657f5-538">Excel</span><span class="sxs-lookup"><span data-stu-id="657f5-538">Excel</span></span>

- <span data-ttu-id="657f5-539">Исправлена проблема, из-за которой использование данных в реальном времени в сочетании с функцией многопоточного пересчета могло привести к неожиданному закрытию приложения.</span><span class="sxs-lookup"><span data-stu-id="657f5-539">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="657f5-540">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="657f5-540">PowerPoint</span></span>

- <span data-ttu-id="657f5-541">Исправлена проблема, из-за которой некоторые поврежденные файлы PowerPoint открывались неправильно даже после восстановления документа.</span><span class="sxs-lookup"><span data-stu-id="657f5-541">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="657f5-542">Word</span><span class="sxs-lookup"><span data-stu-id="657f5-542">Word</span></span>

- <span data-ttu-id="657f5-543">Исправлена ошибка с расширениями комментариев, когда ответ на комментарий имел такое же расширение, что и родительский комментарий.</span><span class="sxs-lookup"><span data-stu-id="657f5-543">Fixes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1908-january-12"></a><span data-ttu-id="657f5-545">Версия 1908: 12 января</span><span class="sxs-lookup"><span data-stu-id="657f5-545">Version 1908: January 12</span></span>
<span data-ttu-id="657f5-546">*Версия 1908 (сборка 11929.20994)*</span><span class="sxs-lookup"><span data-stu-id="657f5-546">*Version 1908 (Build 11929.20994)*</span></span>

<span data-ttu-id="657f5-547">Обновления для системы безопасности перечислены [здесь](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="657f5-547">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="657f5-549">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="657f5-549">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="657f5-550">Набор Office</span><span class="sxs-lookup"><span data-stu-id="657f5-550">Office Suite</span></span>

- <span data-ttu-id="657f5-551">Это изменение решает проблему, связанную с открытием файлов, содержащих устаревшие схемы.</span><span class="sxs-lookup"><span data-stu-id="657f5-551">This change addresses an issue related to opening files containing legacy diagrams.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="657f5-554">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="657f5-554">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (|Win32|DC|Production| |16.0.13127.21668|version-2008-june-08|)
[//]: # (|Win32|DC|Production| |16.0.13127.21624|version-2008-may-11|)
[//]: # (|Win32|DC|Production| |16.0.13127.21506|version-2008-april-13|)
[//]: # (|Win32|DC|Production| |16.0.13127.21348|version-2008-march-09|)
[//]: # (|Win32|DC|Production| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|DC|Production| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|DC|Production| |16.0.12527.21416|version-2002-december-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|version-2002-november-10|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (НЕ ИЗМЕНЯТЬ МЕТАДАННЫЕ ЦЕНТРА АДМИНИСТРИРОВАНИЯ КОНЕЦ СОДЕРЖИМОГО)
