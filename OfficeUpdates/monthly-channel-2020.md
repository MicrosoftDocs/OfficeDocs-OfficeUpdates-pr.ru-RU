---
title: Заметки о выпусках Monthly Channel в 2020 г.
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Заметки о выпусках Monthly Channel для Office 365 профессиональный плюс в 2020 г. для ИТ-специалистов
ms.openlocfilehash: f7255ceead96026615d4e8a8c56826ebf53c41b3
ms.sourcegitcommit: 220736aa7c6bf7466beba7f3291f068546c3c77e
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/21/2020
ms.locfileid: "42228368"
---
# <a name="release-notes-for-monthly-channel-releases-in-2020"></a><span data-ttu-id="d2167-103">Заметки о выпусках Monthly Channel в 2020 г.</span><span class="sxs-lookup"><span data-stu-id="d2167-103">Release notes for Monthly Channel releases in 2020</span></span>

<span data-ttu-id="d2167-104">В этих заметках о выпусках содержатся сведения о новых функциях и обновлениях, не связанных с безопасностью, включенных в обновления Monthly Channel для Office 365 профессиональный плюс в 2020 г., Visio Pro для Office 365, классический клиент Project Online и Office 365 бизнес.</span><span class="sxs-lookup"><span data-stu-id="d2167-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2020, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="d2167-105">Мы часто выпускаем функции (а иногда даже исправления) для Monthly Channel по истечении определенного времени.</span><span class="sxs-lookup"><span data-stu-id="d2167-105">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span>  <span data-ttu-id="d2167-106">Если у вас пока нет каких-либо из перечисленных ниже возможностей, они скоро появятся.</span><span class="sxs-lookup"><span data-stu-id="d2167-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="d2167-107">Подробнее</span><span class="sxs-lookup"><span data-stu-id="d2167-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="d2167-108">Microsoft Teams для существующих установок Office 365 профессиональный плюс — с начала июля обновления Office 365 профессиональный плюс (и Office 365 бизнес) будут включать Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="d2167-108">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in early July, updates to Office 365 ProPlus (and Office 365 Business) will include Microsoft Teams.</span></span>  <span data-ttu-id="d2167-109">Дата добавления приложения Teams зависит от используемого канала обновления.</span><span class="sxs-lookup"><span data-stu-id="d2167-109">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="d2167-110">Дополнительные сведения см. в статье [Развертывание Microsoft Teams с Office 365 профессиональный плюс](https://docs.microsoft.com/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="d2167-110">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

## <a name="version-2001-february-19"></a><span data-ttu-id="d2167-111">Версия 2001: 19 февраля</span><span class="sxs-lookup"><span data-stu-id="d2167-111">Version 2001: February 19</span></span>
<span data-ttu-id="d2167-112">*Версия 2001 (сборка 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="d2167-112">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="d2167-113">Исправления различных ошибок и улучшения производительности.</span><span class="sxs-lookup"><span data-stu-id="d2167-113">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="d2167-114">Версия 2001: 11 февраля</span><span class="sxs-lookup"><span data-stu-id="d2167-114">Version 2001: February 11</span></span>
<span data-ttu-id="d2167-115">*Версия 2001 (сборка 12430,20264)*</span><span class="sxs-lookup"><span data-stu-id="d2167-115">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="d2167-116">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d2167-116">Security updates listed [here](https://docs.microsoft.com/ru-RU/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="d2167-118">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="d2167-118">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d2167-119">Access</span><span class="sxs-lookup"><span data-stu-id="d2167-119">Access</span></span>

- <span data-ttu-id="d2167-120">В случае, если в базе данных не будет сбоев вложенных столбцов, они больше не должны возникать.</span><span class="sxs-lookup"><span data-stu-id="d2167-120">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="d2167-121">После создания шаблона вы можете добавить в базу данных поле вложения.</span><span class="sxs-lookup"><span data-stu-id="d2167-121">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="d2167-122">Excel</span><span class="sxs-lookup"><span data-stu-id="d2167-122">Excel</span></span>

- <span data-ttu-id="d2167-123">Исправлена проблема, в которой не отображаются команды примечаний в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="d2167-123">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="d2167-124">Исправлена проблема, из-за которой некоторые пользователи могут столкнуться с ошибками при преобразовании текста в столбцы с ячейками, в которых есть массив для переноса.</span><span class="sxs-lookup"><span data-stu-id="d2167-124">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="d2167-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2167-125">Outlook</span></span>

- <span data-ttu-id="d2167-126">Решает проблему, из-за которой у пользователей возникал сбой при указании неверного адреса От.</span><span class="sxs-lookup"><span data-stu-id="d2167-126">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="d2167-127">Решает проблему, которая приводила к сбою пользователей при отмене настройки учетной записи.</span><span class="sxs-lookup"><span data-stu-id="d2167-127">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="d2167-128">Project</span><span class="sxs-lookup"><span data-stu-id="d2167-128">Project</span></span>

- <span data-ttu-id="d2167-129">Исправлена ошибка, из-за которой 100% задач с фиксированной продолжительностью могут ошибочно рассчитывать% выполнения при завершении менее чем на 100%.</span><span class="sxs-lookup"><span data-stu-id="d2167-129">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d2167-130">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d2167-130">Office Suite</span></span>

- <span data-ttu-id="d2167-131">Это изменение устраняет проблемы с графическими адаптерами, использующими встроенный графический процессор Intel.</span><span class="sxs-lookup"><span data-stu-id="d2167-131">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-2001-january-30"></a><span data-ttu-id="d2167-133">Версия 2001: 30 января</span><span class="sxs-lookup"><span data-stu-id="d2167-133">Version 2001: January 30</span></span>
<span data-ttu-id="d2167-134">*Версия 2001 (сборка 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="d2167-134">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="d2167-136">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="d2167-136">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d2167-137">Excel</span><span class="sxs-lookup"><span data-stu-id="d2167-137">Excel</span></span>

- <span data-ttu-id="d2167-138">**Быстрое прочтение и ответ.** Отвечайте на примечания и упоминания прямо в сообщении электронной почты, не открывая книгу.</span><span class="sxs-lookup"><span data-stu-id="d2167-138">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="d2167-139">**Посмотрите налево, посмотрите направо… ПРОСМОТРX уже доступен!:** построчно просмотрите и найдите нужные элементы в таблице или диапазоне с помощью функции ПРОМОТРX.</span><span class="sxs-lookup"><span data-stu-id="d2167-139">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="d2167-140">Подробнее</span><span class="sxs-lookup"><span data-stu-id="d2167-140">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="d2167-141">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2167-141">Outlook</span></span>

- <span data-ttu-id="d2167-142">**Дополнительные параметры электронной почты группы.** Эта функция позволяет группам пользователей настраивать сообщения или события, получаемые и отслеживаемые в папке "Входящие".</span><span class="sxs-lookup"><span data-stu-id="d2167-142">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="d2167-143">**Политика именования групп.** Политика именования групп позволяет ИТ-администратору стандартизировать имена групп, созданных пользователями в организации, а также управлять ими.</span><span class="sxs-lookup"><span data-stu-id="d2167-143">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="d2167-144">Администратор может требовать добавления специального префикса и суффикса к имени группы при ее создании и может запретить использование определенных слов.</span><span class="sxs-lookup"><span data-stu-id="d2167-144">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="d2167-145">Это позволяет уменьшить использование недопустимых слов в названиях групп, а также управлять отображением групп в каталоге.</span><span class="sxs-lookup"><span data-stu-id="d2167-145">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="d2167-146">Политика именования также помогает организациям развертывать сайты групп для их классификации по отделам.</span><span class="sxs-lookup"><span data-stu-id="d2167-146">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="d2167-147">Word</span><span class="sxs-lookup"><span data-stu-id="d2167-147">Word</span></span>

- <span data-ttu-id="d2167-148">**Более безопасная работа с видео.** Улучшения системы безопасности означают более защищенный интерфейс работы с видео из Интернета.</span><span class="sxs-lookup"><span data-stu-id="d2167-148">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="d2167-149">Подробнее</span><span class="sxs-lookup"><span data-stu-id="d2167-149">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="d2167-150">**Лассо для рукописных фрагментов.** С помощью инструмента "лассо" на вкладке "Рисование" можно выбрать объекты, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="d2167-150">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="d2167-151">Выделяйте отдельные фрагменты или целые слова.</span><span class="sxs-lookup"><span data-stu-id="d2167-151">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="d2167-152">Подробнее</span><span class="sxs-lookup"><span data-stu-id="d2167-152">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="d2167-153">**Сохранение фигур в виде рисунков.** С помощью всего пары щелчков вы можете сохранить фигуру, значок и другой объект в виде файла рисунка, чтобы его можно было использовать в другом месте.</span><span class="sxs-lookup"><span data-stu-id="d2167-153">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="d2167-154">Подробнее</span><span class="sxs-lookup"><span data-stu-id="d2167-154">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="d2167-157">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="d2167-157">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d2167-158">Access</span><span class="sxs-lookup"><span data-stu-id="d2167-158">Access</span></span>

- <div><span data-ttu-id="d2167-159"><span style="display:inline !important;">Это обновление исправляет проблему, из-за которой при использовании объекта ADODB.Recorder в коде VB может необоснованно появляться сообщение об ошибке.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="d2167-159"><span style="display:inline !important;">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.&nbsp;</span></span></span><br></div>


- <div style="box-sizing:border-box;"><span data-ttu-id="d2167-160"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных</span></span></span><span class="sxs-lookup"><span data-stu-id="d2167-160"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly</span></span></span></span></div>


### <a name="excel"></a><span data-ttu-id="d2167-161">Excel</span><span class="sxs-lookup"><span data-stu-id="d2167-161">Excel</span></span>

- <div><span data-ttu-id="d2167-162">Исправлена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="d2167-162">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="d2167-163">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2167-163">Outlook</span></span>

- <div><span data-ttu-id="d2167-164">Исправлена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="d2167-164">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>


### <a name="outlookexe"></a><span data-ttu-id="d2167-165">outlook.exe</span><span class="sxs-lookup"><span data-stu-id="d2167-165">outlook.exe</span></span>

- <div><span data-ttu-id="d2167-166">Исправлена проблема, приводившая к сбоям при переименовании подписи.</span><span class="sxs-lookup"><span data-stu-id="d2167-166">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-january-22"></a><span data-ttu-id="d2167-168">Версия 1912: 22 января</span><span class="sxs-lookup"><span data-stu-id="d2167-168">Version 1912: January 22</span></span>
<span data-ttu-id="d2167-169">*Версия 1912 (сборка 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="d2167-169">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="d2167-171">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="d2167-171">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d2167-172">Access</span><span class="sxs-lookup"><span data-stu-id="d2167-172">Access</span></span>

- <div><span data-ttu-id="d2167-173">Это обновление исправляет проблему, из-за которой Microsoft Access не удавалось определить столбец идентификаторов в связанной таблице SQL Server, что могло приводить к неправильному указанию строк как удаленных</span><span class="sxs-lookup"><span data-stu-id="d2167-173">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1912-january-14"></a><span data-ttu-id="d2167-175">Версия 1912: 14 января</span><span class="sxs-lookup"><span data-stu-id="d2167-175">Version 1912: January 14</span></span>
<span data-ttu-id="d2167-176">*Версия 1912 (сборка 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="d2167-176">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="d2167-177">Обновления для системы безопасности перечислены [здесь](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d2167-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="d2167-178">Версия 1912: 8 января</span><span class="sxs-lookup"><span data-stu-id="d2167-178">Version 1912: January 08</span></span>
<span data-ttu-id="d2167-179">*Версия 1912 (сборка 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="d2167-179">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="d2167-181">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="d2167-181">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="d2167-182">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2167-182">Outlook</span></span>

- <span data-ttu-id="d2167-183">**Отправка писем со специальными возможностями пользователям, которым они нужны.** Outlook отображает подсказку, помогающую обеспечить доступность контента при отправке пользователю, который предпочитает контент с поддержкой специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="d2167-183">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d2167-184">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d2167-184">PowerPoint</span></span>

- <span data-ttu-id="d2167-185">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="d2167-185">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="d2167-186">**Быстрое создание GIF.** Один слайд, один кадр.</span><span class="sxs-lookup"><span data-stu-id="d2167-186">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="d2167-187">Легко создавайте циклические GIF-изображения в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="d2167-187">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="d2167-188">Подробнее</span><span class="sxs-lookup"><span data-stu-id="d2167-188">Learn more</span></span>](https://support.office.com/ru-RU/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="d2167-191">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="d2167-191">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d2167-192">Excel</span><span class="sxs-lookup"><span data-stu-id="d2167-192">Excel</span></span>

- <span data-ttu-id="d2167-193">Это изменение обходит проблему, связанную с некоторыми графическими драйверами Intel, благодаря использованию программной отрисовки.</span><span class="sxs-lookup"><span data-stu-id="d2167-193">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="d2167-194">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2167-194">Outlook</span></span>

- <span data-ttu-id="d2167-195">Исправлена проблема, из-за которой место проведения собрания неожиданно вновь добавлялось к собранию после его очистки.</span><span class="sxs-lookup"><span data-stu-id="d2167-195">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="d2167-196">Исправлена проблема, приводившая к возникновению у пользователей заметных задержек при взаимодействии с папками почтового ящика с помощью сочетаний клавиш.</span><span class="sxs-lookup"><span data-stu-id="d2167-196">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="d2167-197">Исправлена проблема, из-за которой пользователи иногда сталкивались с отправкой сообщений на адрес, не соответствующий отображавшемуся SMTP-адресу.</span><span class="sxs-lookup"><span data-stu-id="d2167-197">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="d2167-198">Исправлена проблема, приводившая к зависаниям у пользователей в Outlook при получении облачных параметров.</span><span class="sxs-lookup"><span data-stu-id="d2167-198">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="d2167-199">Word</span><span class="sxs-lookup"><span data-stu-id="d2167-199">Word</span></span>

- <span data-ttu-id="d2167-200">Диспетчер стандартных блоков может отображать неправильное оповещение: &quot;Были изменены стили, стандартные блоки&quot;.</span><span class="sxs-lookup"><span data-stu-id="d2167-200">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d2167-201">Набор Office</span><span class="sxs-lookup"><span data-stu-id="d2167-201">Office Suite</span></span>

- <span data-ttu-id="d2167-202">Решена проблема, из-за которой обновления Office могли неожиданно скачать файлы из Office CDN вместо намеченного источника, такого как локальная или сетевая папка или расположение, предоставленное Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="d2167-202">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

> [!NOTE]
> <span data-ttu-id="d2167-204">Если вам нужна помощь с использованием Office, рекомендуем задать вопрос на [форуме](https://answers.microsoft.com/) или в [сообществе](https://techcommunity.microsoft.com/) или связаться со [службой поддержки](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="d2167-204">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
