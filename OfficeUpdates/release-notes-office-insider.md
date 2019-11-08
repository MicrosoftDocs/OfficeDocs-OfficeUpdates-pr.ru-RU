---
title: Заметки о выпуске для участников программы предварительной оценки Office
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Предоставляет участникам программы предварительной оценки с ранним доступом последний список ключевых новых функций, исправлений или известных проблем
ms.openlocfilehash: 81474ca6ba2e2cce145dfc8b80dff8c8b2857541
ms.sourcegitcommit: e7eb58247abb6fc7f7082e98ae4847344f35a69e
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/02/2019
ms.locfileid: "37931913"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="a7fcd-103">Заметки о выпуске для участников программы предварительной оценки Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="a7fcd-104">Эта статья содержит заметки о выпуске для сборок приложений Word, Excel, PowerPoint, Outlook, Access и Project для Windows, предоставляемых в рамках программы предварительной оценки.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a7fcd-105">Каждую неделю мы будем сообщать об интересных новых возможностях, важных исправлениях и существенных проблемах, о которых вам следует знать.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a7fcd-106">Обратите внимание на то, что развертывание возможностей (а иногда даже исправлений) для участников программы предварительной оценки зачастую занимает определенное время.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="a7fcd-107">Благодаря этому мы обеспечиваем стабильную работу возможностей до того, как они становятся доступны более широкой аудитории.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a7fcd-108">Если вы не видите чего-либо из описанного ниже, не беспокойтесь, вы получите это позже.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="a7fcd-109">Заметки о выпуске публикуются еженедельно и могут представлять собой компиляцию для нескольких сборок</span><span class="sxs-lookup"><span data-stu-id="a7fcd-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="a7fcd-110">Дата публикации заметок о выпуске может не совпадать с фактической датой выпуска сборки</span><span class="sxs-lookup"><span data-stu-id="a7fcd-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="a7fcd-111">Microsoft Teams для существующих установок Office 365 профессиональный плюс — с конца июня Microsoft Teams будет добавляться в существующие установки Office 365 профессиональный плюс (и Office 365 бизнес) при обновлении этих установок.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="a7fcd-112">Дата добавления приложения Teams зависит от используемого канала обновления.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="a7fcd-113">Дополнительные сведения см. в статье [Развертывание Microsoft Teams с Office 365 профессиональный плюс](https://docs.microsoft.com/ru-RU/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="a7fcd-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/ru-RU/deployoffice/teams-install) for additional information.</span></span>

[//]: # (НЕ УДАЛЯТЬ)


## <a name="version-1911-november-01"></a><span data-ttu-id="a7fcd-115">Версия 1911: 1 ноября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-115">Version 1911: November 01</span></span>
<span data-ttu-id="a7fcd-116">*Версия 1911 (сборка 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-116">*Version 1911 (Build 12215.20006)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a7fcd-118">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-118">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-119">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-119">Excel</span></span>

- <span data-ttu-id="a7fcd-120">**Использование контекста вместе с объектами SVG.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Office.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-120">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office</span></span>

- <span data-ttu-id="a7fcd-121">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-121">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-122">PowerPoint</span></span>

- <span data-ttu-id="a7fcd-123">**Использование контекста вместе с объектами SVG.** Теперь можно сохранять текст на картах, диаграммах и других изображениях SVG при преобразовании таких объектов в Office.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-123">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office</span></span>

- <span data-ttu-id="a7fcd-124">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-124">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="a7fcd-125">Visio</span><span class="sxs-lookup"><span data-stu-id="a7fcd-125">Visio</span></span>

- <span data-ttu-id="a7fcd-126">**Создание привлекательных схем Visio в Excel.** Быстро и легко визуализируйте свои данные, превращая их в привлекательные схемы Visio в Excel.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-126">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="a7fcd-127">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-127">Learn more</span></span>](https://support.office.com/ru-RU/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="a7fcd-128">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-128">Word</span></span>

- <span data-ttu-id="a7fcd-129">**Просмотр параметров ручки при выборе ручки Surface.** При выборе ручки Surface в программах Word, Excel и PowerPoint в первый раз активируется вкладка рисования, на которой без труда можно выбрать цвет ручки.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-129">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="a7fcd-130">**Улучшенные возможности совместного редактирования.** Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-130">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="a7fcd-131">**Другие пользователи быстро просматривают внесенные вами изменения.** С улучшенными функциями совместного редактирования участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо прежде.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-131">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a7fcd-134">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-134">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-135">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-135">Excel</span></span>

- <div><span data-ttu-id="a7fcd-136"><span>Исправлена проблема, из-за которой мог происходить сбой программы Excel при изменении защищенного файла из ненадежного сетевого ресурса.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-136"><span>Resolved an issue where Excel may crash when editing a protected file from an untrusted network share</span></span></span></div>


- <div><span data-ttu-id="a7fcd-137">Исправлена проблема, из-за которой удаление листов, содержащих спарклайны со ссылками на данные других листов, могло привести к обозначению файла как поврежденного при повторном открытии.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-137">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span></div>


- <div><span data-ttu-id="a7fcd-138">Устранена проблема, из-за которой можно было получить неверный результат при преобразовании фильтров отчета вместе с остальной частью сводной таблицы для запросов на серверы таблиц SQL.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-138">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span></span></div>


- <div><span data-ttu-id="a7fcd-139"><span>Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-139"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


- <div><span data-ttu-id="a7fcd-140"><span>Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-140"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-141">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-141">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-142">Перенаправленная электронная почта может лишиться вложенных изображений.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-142">A forwarded e-mail may be missing embedded images</span></span></div>


- <div><span data-ttu-id="a7fcd-143"><span>Средство поиска помещений может отображать значение &quot;Нет&quot; для доступных помещений.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-143"><span>Room Finder tool may be displaying &quot;None&quot; for available rooms</span></span></span></div>


- <div><span data-ttu-id="a7fcd-144"><span>Пользователи могут не иметь возможности создавать профили Outlook со строгим ограничением клиента.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-144"><span>Users may not be able to create Outlook profiles with strict tenant restriction</span></span></div></span>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-145">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-145">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-146"><span>Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-146"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


### <a name="project"></a><span data-ttu-id="a7fcd-147">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-147">Project</span></span>

- <div><span data-ttu-id="a7fcd-148"><span>Пользователь не может отметить задачу как завершенную, и ее выполнение остается на уровне 99 %.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-148"><span>User is unable to mark a task as complete, and it gets set to 99%</span></span></span></div>


- <div><span data-ttu-id="a7fcd-149">Превышения доступности не устраняются выравниванием.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-149">Overallocations are not resolved by leveling</span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-150">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-150">Word</span></span>

- <div><span data-ttu-id="a7fcd-151"><span>Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-151"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


- <div><span data-ttu-id="a7fcd-152"><span>Открытие устаревших документов с последующим переходом на вкладку "Сведения" может привести к сбою.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-152"><span>Opening legacy documents and then going to the Info tab can cause a crash</span></span></span></div>


- <div><span data-ttu-id="a7fcd-153"><span>Предложения проверки не отображаются в контекстных меню.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-153"><span>Proofing suggestins are not displaying in contextual menus</span></span></span></div>


- <div><span data-ttu-id="a7fcd-154"><span>Политики содержимого применяются к комментариям некорректно.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-154"><span>Content policies are being incorrectly applied to comments</span></span></span></div>


- <div><span data-ttu-id="a7fcd-155"><span>Старые комментарии, написанные темным текстом, не удается увидеть в темном режиме.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-155"><span>Legacy comments written with dark text is not visible in Dark Mode</span></span></span></div>


- <div><span data-ttu-id="a7fcd-156"><span>При использовании автозамены в языковой паре корейский-английский могут отображаться некорректные символы.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-156"><span>Incorrect characters may appear when using Korean/English autocorrect</span></span></span></div>


- <div><span data-ttu-id="a7fcd-157"><span>Могут применяться метки менее строгих политик, когда приоритет должна иметь метка более строгой политики.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-157"><span>Lower policy labels may be applied when a higher policy label should have taken priority</span></span></div></span>


- <div><span data-ttu-id="a7fcd-158"><span>Ссылки cid: теперь связь с изображениями из сообщений Outlook&nbsp;может быть успешно разорвана по запросу.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-158"><span>The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span></div></span>


- <div><span data-ttu-id="a7fcd-159"><span>Одновременное использование экранного диктора и экранной лупы может привести к сбою.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-159"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


- <div><span data-ttu-id="a7fcd-160"><span>Поиск из области навигации может завершаться неудачей.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-160"><span>Searching from the Navigation pane may fail</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-161">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-161">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-162"><span>Некоторые рисунки могут не отображаться в предварительном просмотре или в слайд-шоу.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-162"><span>Some drawings may not display in preview or slide shows</span></span></span></div>


- <div><span data-ttu-id="a7fcd-163"><span>Символы катаканы могут неправильно отображаться в вертикальной надписи.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-163"><span>Some katakana characters may display incorrectly in a vertical text box</span></span></span></div>


- <div><span data-ttu-id="a7fcd-164">Попытка сохранить файл в сетевой папке, с которой потеряна связь, может привести к сбою.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-164">Attempting to save a file to a disconnected network share may result in a crash</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-october-25"></a><span data-ttu-id="a7fcd-166">Версия 1911: 25 октября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-166">Version 1911: October 25</span></span>
<span data-ttu-id="a7fcd-167">*Версия 1911 (сборка 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-167">*Version 1911 (Build 12215.20006)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a7fcd-169">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-169">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="a7fcd-170">Visio</span><span class="sxs-lookup"><span data-stu-id="a7fcd-170">Visio</span></span>

- <span data-ttu-id="a7fcd-171">**Создание привлекательных схем Visio в Excel.** Быстро и легко визуализируйте свои данные, превращая их в привлекательные схемы Visio в Excel.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-171">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="a7fcd-172">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-172">Learn more</span></span>](https://support.office.com/ru-RU/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="a7fcd-173">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-173">Word</span></span>

- <span data-ttu-id="a7fcd-174">**Улучшенные возможности совместного редактирования.** Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-174">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="a7fcd-175">**Другие пользователи быстро просматривают внесенные вами изменения.** С улучшенными функциями совместного редактирования участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо прежде.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-175">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="resolved-issues"></a><span data-ttu-id="a7fcd-178">Решенные проблемы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-178">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a7fcd-179">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-179">Access</span></span>

- <div><span data-ttu-id="a7fcd-180"><span>Число записей может быть неверным</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-180"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="a7fcd-181">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-181">Excel</span></span>

- <div><span data-ttu-id="a7fcd-182"><span>Значительно повышена производительность при удалении столбцов с объединенными ячейками</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-182"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="a7fcd-183"><span>Пользователям не удается сохранять записи в формате книги Excel в Office 365</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-183"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="a7fcd-184"><span>Флажки могут отображаться неправильно</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-184"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="a7fcd-185"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-185"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="a7fcd-186"><span>Некоторые функции VBA возвращают ошибку в новых типах диаграмм</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-186"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="a7fcd-187"><span>В диалоговых окнах "Выбор источника данных" не учитывается регистр для некоторых полей</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-187"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-188">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-189"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-189"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="a7fcd-190">Publisher</span><span class="sxs-lookup"><span data-stu-id="a7fcd-190">Publisher</span></span>

- <div><span data-ttu-id="a7fcd-191"><span>Фигуры могут отображаться за пределами границы рисунка</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-191"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-192">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-192">Word</span></span>

- <div><span data-ttu-id="a7fcd-193"><span>Фигуры могут отображаться за пределами границы рисунка</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-193"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="a7fcd-194"><span>Обтекание текста может оказаться трудной задачей</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-194"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="a7fcd-195"><span>Пользователю не удается перейти к отдельному элементу в редакторе</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-195"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="a7fcd-196"><span>Грамматические и орфографические ошибки могут не выделяться</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-196"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="a7fcd-197"><span>Изменения размеров диаграммы могут не сохраняться</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-197"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="a7fcd-198"><span>Не удается открыть карточку контакта после применения форматирования к @упоминанию</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-198"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="a7fcd-199"><span>Решена проблема, из-за которой пользователям не удается сохранить документы Word, Excel и PowerPoint.&nbsp; Эта проблема возникает у пользователей, создающих файл и использующих параметр &quot;Сохранить как модельное диалоговое окно&quot; после щелчка по значку "Сохранить" или нажатия клавиш CTRL+S.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-199"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-200">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-200">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-201"><span>Проблема с производительностью при использовании фигур в Windows 7</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-201"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1911-october-18"></a><span data-ttu-id="a7fcd-203">Версия 1911: 18 октября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-203">Version 1911: October 18</span></span>
<span data-ttu-id="a7fcd-204">*Версия 1911 (сборка 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-204">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a7fcd-206">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-206">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a7fcd-207">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-207">Outlook</span></span>

- <span data-ttu-id="a7fcd-208">**Отправка писем со специальными возможностями пользователям, которым они нужны.** Outlook отображает подсказку, помогающую обеспечить доступность контента при отправке пользователю, который предпочитает контент с поддержкой специальных возможностей.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-208">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-209">PowerPoint</span></span>

- <span data-ttu-id="a7fcd-210">**Оптимизация презентации для всех пользователей.** Средство проверки читаемости помогает расположить объекты на слайдах с учетом средств чтения с экрана.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-210">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a7fcd-211">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-211">Office Suite</span></span>

- <span data-ttu-id="a7fcd-212">**Центр отправки заменяется интерфейсом "Файлы, требующие внимания".** Центр отправки заменяется интерфейсом "Файлы, требующие внимания", доступным в приложениях Office в разделе "Файл" > "Открыть".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-212">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="a7fcd-213">Этот новый интерфейс более современный, интегрированный и менее навязчивый по сравнению с Центром отправки.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-213">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-216">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-216">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-217">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-217">Excel</span></span>

- <div><span data-ttu-id="a7fcd-218"><span>Исправлена проблема, из-за которой флажки могли сжиматься при использовании функции автоподбора для настройки высоты строки</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-218"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="a7fcd-219"><span>Исправлена проблема, из-за которой выбор ячейки после прокрутки мог приводить к выбору неправильной ячейки</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-219"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-220">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-220">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-221"><span>Обнаружена проблема, которая может вызывать нарушение цифровых подписей при подписании сообщения, содержащего вложение с цифровой подписью</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-221"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="a7fcd-222"><span>Обнаружена проблема, из-за которой длинные имена файлов усекались после перетаскивания в текст сообщения</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-222"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="a7fcd-223">Обнаружена проблема, из-за которой поле поиска может исчезать, если лента настроена на автоматическое скрытие</span><span class="sxs-lookup"><span data-stu-id="a7fcd-223">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-224">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-224">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-225"><span>Обнаружена проблема, из-за которой пропорции при предварительном просмотре слайда блокировались или разблокировались неправильно.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-225"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a7fcd-226">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-226">Project</span></span>

- <div><span data-ttu-id="a7fcd-227">Обнаружена проблема, из-за которой примечания могут не сохраняться, если вводятся при выполнении задач обновления</span><span class="sxs-lookup"><span data-stu-id="a7fcd-227">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="a7fcd-228">Обнаружена проблема, из-за которой файл может блокироваться пользователем, но в сообщении об ошибке не отображается имя пользователя</span><span class="sxs-lookup"><span data-stu-id="a7fcd-228">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="a7fcd-229"><span>Обнаружена проблема, из-за которой пользователи могут получать несколько сообщений при открытии проекта только для чтения</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-229"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-230">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-230">Word</span></span>

- <div><span data-ttu-id="a7fcd-231"><span>Выявлена проблема с просмотром примечаний при использовании средства чтения с экрана</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-231"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="a7fcd-232"><span>Обнаружена проблема, из-за которой некоторые замечания неправильно определялись как орфографические или грамматические замечания</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-232"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="a7fcd-233"><span>Обнаружена проблема, из-за которой фокус иногда не перемещается в диалоговое окно создания примечания</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-233"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-234">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-234">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-235"><span>Исправлена проблема, из-за которой обновление могло блокироваться неверным сообщением об ошибке &quot;Уже запущен другой процесс установки&quot;</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-235"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="a7fcd-236"><span>Обнаружена проблема, которая может влиять на синхронизацию локального ресурса с облачным</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-236"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="a7fcd-237"><span>Обнаружена проблема, из-за которой приветственное сообщение содержит неправильную ссылку</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-237"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-october-11"></a><span data-ttu-id="a7fcd-239">Версия 1910: 11 октября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-239">Version 1910: October 11</span></span>
<span data-ttu-id="a7fcd-240">*Версия 1910 (сборка 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-240">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-244">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-244">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-245">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-245">Excel</span></span>

- <div><span data-ttu-id="a7fcd-246">Решена проблема со вставкой файлов в качестве объектов из OneDrive</span><span class="sxs-lookup"><span data-stu-id="a7fcd-246">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="a7fcd-247">Решена проблема, из-за которой не удавалось правильно применять формат гиперссылки к некоторому содержимому</span><span class="sxs-lookup"><span data-stu-id="a7fcd-247">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="a7fcd-248">Решена проблема, из-за которой формулы со структурированными абсолютными ссылками могли изменяться неправильно</span><span class="sxs-lookup"><span data-stu-id="a7fcd-248">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="a7fcd-249">Решена проблема, из-за которой книги, созданные в более ранних версиях Office, могли приводить к зависанию Excel при открытии в текущих версиях Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-249">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="a7fcd-250">Решена проблема, из-за которой содержимое, скопированное из Excel, могло отображаться неправильно при вставке в другие приложения Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-250">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="a7fcd-251">Исправлены цвета, используемые при предварительном просмотре, когда вставляются диаграммы с использованием шаблонов диаграмм</span><span class="sxs-lookup"><span data-stu-id="a7fcd-251">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-252">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-252">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-253">Обнаружена проблема, из-за которой устройства ARC могли терять подключение при работе в AirSpace WinComp</span><span class="sxs-lookup"><span data-stu-id="a7fcd-253">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-254">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-254">Word</span></span>

- <div><span data-ttu-id="a7fcd-255">Решена проблема со вставкой файлов в качестве объектов из OneDrive</span><span class="sxs-lookup"><span data-stu-id="a7fcd-255">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="a7fcd-256">Улучшены этапы восстановления для и<span>справления проблемы, приводившей к удалению графического содержимого из цепочек электронной почты.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-256">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-october-04"></a><span data-ttu-id="a7fcd-258">Версия 1910: 4 октября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-258">Version 1910: October 04</span></span>
<span data-ttu-id="a7fcd-259">*Версия 1910 (сборка 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-259">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a7fcd-261">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-261">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-262">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-262">Excel</span></span>

- <span data-ttu-id="a7fcd-263">**Надстройка "Визуализатор данных".** Быстро создавайте блок-схемы Visio из Excel.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-263">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="a7fcd-264">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-264">Learn more</span></span>](https://support.office.com/ru-RU/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-267">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-267">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-268">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-268">Excel</span></span>

- <div><span data-ttu-id="a7fcd-269"><span>Исправлена проблема, из-за которой при предварительном просмотре неправильно отображалась область печати</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-269"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="a7fcd-270"><span>Исправлена проблема, которая могла блокировать обновление сводных таблиц во время совместного редактирования</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-270"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="a7fcd-271">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-271">Access</span></span>

- <div><span data-ttu-id="a7fcd-272">Исправлена проблема, из-за которой пользователи могли сталкиваться с ошибкой &quot;несогласованного состояния&quot; при использовании общей базы данных.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-272">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-273">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-274"><span>Исправлена проблема, которая могла приводить к дублированию почтовых папок</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-274"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="a7fcd-275"><span>Исправлена проблема, из-за которой могло неправильно возникать сообщение об ошибке при попытке отправить письмо, зашифрованное с помощью S/MIME</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-275"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="a7fcd-276"><span>Исправлена проблема, из-за которой иногда мог возникать сбой при получении пользователем сообщения "Пропущенная беседа" из Skype</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-276"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="a7fcd-277"><span>Исправлена проблема, которая могла приводить к утечке памяти</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-277"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="a7fcd-278"><span>Исправлена проблема, которая могла приводить к изменению имени отправителя при сохранении в виде черновика</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-278"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-279">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-279">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="a7fcd-280">Исправлена проблема, из-за которой могли повреждаться объекты TextRange после вставки текста в колонтитулы или заполнители номеров страниц слайдов в образце слайдов и макете слайдов.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-280">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="a7fcd-281">Исправлена проблема, не позволявшая создавать гиперссылку при вставке текста с гиперссылкой.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-281">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="a7fcd-282">Исправлена проблема, которая могла мешать правильной работе статистических данных.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-282">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-283">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-283">Word</span></span>

- <div><span data-ttu-id="a7fcd-284"><span>Исправлена проблема, из-за которой не фиксировался цвет шрифта</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-284"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-285">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-285">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-286">Исправлена проблема, из-за которой мог предлагаться журнал версий, когда эта функция отключена.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-286">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-27"></a><span data-ttu-id="a7fcd-288">Версия 1910: 27 сентября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-288">Version 1910: September 27</span></span>
<span data-ttu-id="a7fcd-289">*Версия 1910 (сборка 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-289">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)
[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-293">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-293">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-294">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-294">Excel</span></span>

- <div><span data-ttu-id="a7fcd-295"><span>Исправлена проблема, которая могла приводить к неправильному отображению точечных графиков при изменении набора рядов</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-295"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-296">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-296">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-297"><span>Исправлена проблема, которая могла приводить к ошибкам с разрешениями при взаимодействии с общими папками календаря</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-297"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="a7fcd-298"><span>Исправлена проблема, которая могла мешать пользователям добавлять вложения в календари</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-298"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="a7fcd-299"><span>Исправлена проблема, приводившая к появлению сообщений об ошибках при ответе на сообщение с цифровой подписью</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-299"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-300">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-300">Word</span></span>

- <div><span data-ttu-id="a7fcd-301"><span>Исправлена проблема, которая могла приводить к ошибкам с масштабированием при печати на принтерах Deskjet</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-301"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-302">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-302">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-303"><span>Исправлена проблема, из-за которой к полужирному тексту среднего размера могли применяться неправильные стили</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-303"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="a7fcd-304"><span>Исправлена проблема, из-за которой для пользователя могло отображаться неверное сообщение об ошибке при закрытии файла, ожидающего отправки</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-304"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-20"></a><span data-ttu-id="a7fcd-306">Версия 1910: 20 сентября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-306">Version 1910: September 20</span></span>
<span data-ttu-id="a7fcd-307">*Версия 1910 (сборка 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-307">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-311">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-311">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-312">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-312">Excel</span></span>

- <div><span data-ttu-id="a7fcd-313"><span>Исправлена проблема, из-за которой Excel иногда зависал при запуске</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-313"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="a7fcd-314">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-314">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-315"><span>Мы значительно улучшили производительность при выборе помещения, если доступно много помещений</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-315"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="a7fcd-316"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Исправлена проблема, которая могла мешать синхронизации почтовых ящиков клиентов с почтовыми ящиками в Outlook при переходе на современную проверку подлинности в Office 365.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-316"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="a7fcd-317"><span>Исправлена проблема, из-за которой некоторые символы в метках подписей не отображались в выпадающем меню</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-317"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="a7fcd-318">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-318">Project</span></span>

- <div><span data-ttu-id="a7fcd-319"><span>Исправлена проблема, которая могла приводить к сбою при замене корпоративного ресурса локальным ресурсом</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-319"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-320">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-320">Word</span></span>

- <div><span data-ttu-id="a7fcd-321"><span>Исправлена проблема, которая могла мешать правильной работе синхронной прокрутки в режиме черновика</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-321"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="a7fcd-322">Исправлена проблема, из-за которой всплывающие подсказки могли неправильно отображаться после сохранения документа в первый раз</span><span class="sxs-lookup"><span data-stu-id="a7fcd-322">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-13"></a><span data-ttu-id="a7fcd-324">Версия 1910: 13 сентября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-324">Version 1910: September 13</span></span>
<span data-ttu-id="a7fcd-325">*Версия 1910 (сборка 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-325">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-327">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-327">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-328">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-328">Excel</span></span>

- <div><span data-ttu-id="a7fcd-329"><span>Исправлена проблема, которая могла мешать пользователям вставлять гиперссылки в некоторых защищенных листах</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-329"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-330">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-331"><span>Исправлена проблема, из-за которой пользовательский интерфейс мог зависать в компактном представлении</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-331"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-332">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-333"><span>Исправлена проблема, из-за которой у пользователя могла возникать ошибка при печати в PDF</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-333"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="a7fcd-334">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-334">Project</span></span>

- <div><span data-ttu-id="a7fcd-335"><span>Исправлена проблема, из-за которой <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">изменение значения трудозатрат в суммарной задаче могло приводить к сбою при включенной функции защищенных значений трудозатрат</span></span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-335"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="a7fcd-336"><font size=2 style="background-color:rgb(255, 255, 255);">Исправлена проблема, которая могла блокировать возможность синхронизации событий с корпоративными календарями</font></span><span class="sxs-lookup"><span data-stu-id="a7fcd-336"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-337">Набор Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-337">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-338"><span>Исправлена проблема, которая могла приводить к повторному предупреждению об удалении локальных версий файла</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-338"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1910-september-06"></a><span data-ttu-id="a7fcd-340">Версия 1910: 06 сентября</span><span class="sxs-lookup"><span data-stu-id="a7fcd-340">Version 1910: September 06</span></span>
<span data-ttu-id="a7fcd-341">*Версия 1910 (сборка 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-341">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a7fcd-343">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-343">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-344">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-344">Excel</span></span>

- <span data-ttu-id="a7fcd-345">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-345">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a7fcd-346">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-346">Learn more</span></span>](https://support.office.com/ru-RU/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-347">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-347">PowerPoint</span></span>

- <span data-ttu-id="a7fcd-348">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-348">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a7fcd-349">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-349">Learn more</span></span>](https://support.office.com/ru-RU/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="a7fcd-350">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-350">Word</span></span>

- <span data-ttu-id="a7fcd-351">**Подготовка, настройка, рисование.** С ручкой Surface вы готовы к рисованию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-351">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a7fcd-352">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-352">Learn more</span></span>](https://support.office.com/ru-RU/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-355">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-355">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-356">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-356">Excel</span></span>

- <div><span data-ttu-id="a7fcd-357"><span>Исправлена проблема, из-за которой имя шрифта на ленте могло отличаться от используемого шрифта</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-357"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-358">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-358">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-359"><span>Исправлена проблема, которая приводила к неправильному потреблению ресурсов в Outlook при отключении защищенного режима для ограниченных сайтов в Internet Explorer</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-359"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="a7fcd-360"><span>Исправлена проблема, из-за которой при вставке текста из источника ANSI иногда появлялись символы Юникода</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-360"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="a7fcd-361"><span>Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-361"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-362">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-362">Word</span></span>

- <div><span data-ttu-id="a7fcd-363"><span>Исправлена проблема с сохранением форматирования таблиц</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-363"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="a7fcd-364"><span>Исправлена проблема, которая могла приводить к сбою сочетания клавиш CTRL + V</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-364"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="version-1909-august-30"></a><span data-ttu-id="a7fcd-366">Версия 1909: 30 августа</span><span class="sxs-lookup"><span data-stu-id="a7fcd-366">Version 1909: August 30</span></span>
<span data-ttu-id="a7fcd-367">*Версия 1909 (сборка 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="a7fcd-367">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="feature-updates"></a><span data-ttu-id="a7fcd-369">Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-369">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-370">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-370">Access</span></span>

- <span data-ttu-id="a7fcd-371">**Быстрый поиск связанных таблиц.** Наше новое поле поиска облегчает поиск связанных таблиц.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-371">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-372">PowerPoint</span></span>

- <span data-ttu-id="a7fcd-373">**Сохранение изображений в формате SVG.** Сохранение графиков, фигур и других изображений в масштабируемом векторном формате. Можно изменять размер таких изображений без потери качества.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-373">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="a7fcd-374">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-374">Learn more</span></span>](https://support.office.com/ru-RU/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ О ФУНКЦИЯХ КОНЕЦ СОДЕРЖИМОГО)

<br/>

[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ НАЧАЛО СОДЕРЖИМОГО)

### <a name="non-security-updates"></a><span data-ttu-id="a7fcd-377">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-377">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a7fcd-378">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-378">Excel</span></span>

- <div><span data-ttu-id="a7fcd-379"><span>Исправлена проблема, из-за которой возникал конфликт между подсказкой клавиш для функции&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">конфиденциальности </span>и&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">другой подсказкой клавиш.</span></span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-379"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="a7fcd-380"><span>Исправлена проблема, возникавшая при работе с общей книгой при попытке ее сохранения.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-380"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="a7fcd-381"><span>Исправлена проблема, из-за которой в Excel указывались только первые 16 надстроек из значений реестра "\Excel\Add-in Manager".<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-381"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="a7fcd-382"><span>Исправлена проблема, из-за которой функция ЧАСТОТА() возвращает неправильные результаты.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-382"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="a7fcd-383"><span>Значительно повышена производительность фильтрации по цвету.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-383"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="a7fcd-384"><span>Исправлена проблема для пользователей Surface, из-за которой перемещение мыши могло интерпретироваться как событие щелчка мыши.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-384"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="a7fcd-385"><span>Исправлена проблема, не позволявшая использовать навигацию с помощью клавиатуры в диалоговом окне "Найти и заменить".</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-385"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="a7fcd-386"><span>Исправлена проблема, из-за которой неправильно отображались названия некоторых шрифтов.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-386"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="a7fcd-387"><span>Исправлена проблема, препятствовавшая отображению формата CSV в качестве поддерживаемого типа файла</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-387"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="a7fcd-388">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-388">Access</span></span>

- <div><span data-ttu-id="a7fcd-389">Исправлена проблема, из-за которой пользователи могли сталкиваться с ошибкой &quot;несогласованного состояния&quot; при использовании общей базы данных.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-389">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="a7fcd-390"><span>Исправлена проблема, которая могла приводить к появлению элемента управления "Выбор даты", когда этого не требовалось.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-390"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-391">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-391">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-392"><span>Исправлена проблема, из-за которой HTML-содержимое не отображалось для некоторых пользователей POP3.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-392"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="a7fcd-393"><span>Исправлена проблема для удаления неработающей ссылки "Планировщик" из меню переполнения в карточке контакта при работе в средах, в которых этот компонент недоступен.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-393"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="a7fcd-394">OneNote</span><span class="sxs-lookup"><span data-stu-id="a7fcd-394">OneNote</span></span>

- <div><span data-ttu-id="a7fcd-395"><span>Исправлена проблема, связанная с тем, что &nbsp;фоновая синхронизация OneNote иногда перехватывала фокус.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-395"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-396">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-397"><span>Исправлена проблема, которая могла влиять на ориентацию вращения трехмерной вертушки.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-397"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="a7fcd-398"><span>Исправлена проблема, из-за которой некоторые гиперссылки не работали, если они содержали специальные знаки.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-398"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="a7fcd-399"><span>Исправлена проблема, из-за которой одновременно открывалось несколько областей примечаний.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-399"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a7fcd-400">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-400">Project</span></span>

- <div><span data-ttu-id="a7fcd-401"><span>Исправлена проблема, которая могла приводить к сбою после печати представления визуального оптимизатора ресурсов.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-401"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="a7fcd-402">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-402">Word</span></span>

- <div><span data-ttu-id="a7fcd-403"><span>Исправлена проблема, из-за которой многобайтовые знаки в вертикальной надписи отображаются с наложением в режиме чтения.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-403">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="a7fcd-404"><span>Исправлена&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">проблема, из-за которой ресурсы надстроек, связанные с открытками на японском языке, не удается найти, когда пользователь выполняет действия в мастере надстроек.</span></span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-404"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="a7fcd-405"><span>Исправлена проблема, из-за которой могли возникать неполадки с пользовательским интерфейсом строки заголовка окна в режиме защищенного просмотра.</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-405"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="a7fcd-406">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-406">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-407"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Исправлена проблема повреждения файлов при применении действия "Изменить фигуру" к выбранному фрагменту, содержащему обычную фигуру и соединительную линию.</span></span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-407"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="a7fcd-408"><span>Исправлена проблема, <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">приводившая к неполадкам в работе приложений при подключении к нескольким внешним дисплеям или при отключении от них. </span></span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-408"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (НЕ УДАЛЯТЬ СВЕДЕНИЯ ОБ ОШИБКАХ КОНЕЦ СОДЕРЖИМОГО)

## <a name="august-23-2019br"></a><span data-ttu-id="a7fcd-410">**23 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="a7fcd-410">**August 23, 2019**</span></span><br/>
<span data-ttu-id="a7fcd-411">Версия 1909 (сборка 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-411">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="a7fcd-412">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-412">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-413">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-413">Excel</span></span>

- <div><span data-ttu-id="a7fcd-414"><span>Значительно повышена производительность при удалении столбцов с объединенными ячейками</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-414"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-415">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-415">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-416"><span>Исправлена проблема, которая могла препятствовать отображению некоторых символов Юникода при просмотре в браузере</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-416"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a7fcd-417">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-417">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-418"><span>Исправлена проблема, которая могла препятствовать сохранению файлов в папке WebDAV</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-418"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-419">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-420"><span>Исправлена проблема, из-за которой при щелчке пользователя по одному примечанию выделялось другое примечание</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-420"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="a7fcd-421">**16 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="a7fcd-421">**August 16, 2019**</span></span><br/>
<span data-ttu-id="a7fcd-422">Версия 1909 (сборка 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-422">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a7fcd-423">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-423">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a7fcd-424">**Печать номеров слайдов на раздаточных материалах.** Номера слайдов автоматически добавляются в раздаточные материалы.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-424">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="a7fcd-425">Вы сами решаете, оставить или отключить их.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-425">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a7fcd-426">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-426">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-427">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-427">Excel</span></span>

- <div><span data-ttu-id="a7fcd-428"><span>Исправлена проблема, которая приводила к включению функции автосохранения</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-428"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="a7fcd-429">Исправлена проблема, которая приводила к неточному измерению высоты ячеек</span><span class="sxs-lookup"><span data-stu-id="a7fcd-429">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a7fcd-430">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-430">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-431"><span>Исправлена проблема, благодаря чему значительно улучшилась производительность функции примечаний</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-431"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="a7fcd-432"><span>Исправлена проблема, которая могла приводить к сбою при использовании клавиш со стрелками во время поиска</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-432"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="a7fcd-433"><span>Исправлена проблема, из-за которой @упоминание было недоступным, если символ @ стоял после определенных символов</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-433"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="a7fcd-434"><span>Исправлена проблема, которая могла приводить к сбою при удалении @упоминаний</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-434"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="a7fcd-435"><span>Исправлена проблема, из-за которой эмодзи могли неправильно отображаться в карточках примечаний</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-435"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="a7fcd-436"><span>Исправлена проблема с активным буфером обмена, которая могла приводить к сбою</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-436"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="a7fcd-437"><span>Исправлена проблема, которая могла приводить к прекращению работы кнопок на панели быстрого доступа</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-437"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="a7fcd-438"><span>Исправлена проблема, из-за которой предварительный просмотр форматирования документа мог не переключаться на задний план</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-438"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="a7fcd-439">OneNote</span><span class="sxs-lookup"><span data-stu-id="a7fcd-439">OneNote</span></span>

- <span data-ttu-id="a7fcd-440">Исправлена проблема, из-за которой имена разделов не отображаются в раскрывающемся списке разделов, если для темы Office задано значение "черная".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-440">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-441">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-441">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-442"><span>Исправлена проблема с отправкой событий, из-за которой приложение Outlook могло периодически терять фокус</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-442"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="a7fcd-443"><span>Исправлена проблема, из-за которой не работало сочетание клавиш для помещения ответа в папку</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-443"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-444">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-444">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-445"><span>Исправлена проблема с режимом защищенного просмотра, из-за которой иногда возникали проблемы при совместной работе</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-445"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="a7fcd-446"><span>Исправлена проблема, которая приводила к неправильному отображению задач в области примечаний</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-446"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="a7fcd-447"><span>Исправлена проблема, которая могла приводить к сбою при вставке новых слайдов</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-447"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="a7fcd-448">Жизненный цикл пользователя</span><span class="sxs-lookup"><span data-stu-id="a7fcd-448">User Lifecycle</span></span>

- <div><span data-ttu-id="a7fcd-449"><span>Исправлена проблема, из-за которой могла быть недоступна возможность подписки</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-449"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a7fcd-450">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-450">Word</span></span>

- <div><span data-ttu-id="a7fcd-451"><span>Исправлена проблема, из-за которой гиперссылки не работали, если содержали определенные символы</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-451"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="a7fcd-452"><span>Исправлена проблема, из-за которой размеры изображения могли изменяться при просмотре примечаний к нему</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-452"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="a7fcd-453"><span>Исправлена проблема с раскрывающимся меню маркированного списка, которая могло приводить к сбою</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-453"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="a7fcd-454">**9 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="a7fcd-454">**August 09, 2019**</span></span><br/>
<span data-ttu-id="a7fcd-455">Версия 1909 (сборка 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-455">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="a7fcd-456">Обновления функций Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-456">Excel Feature updates:</span></span>

- <span data-ttu-id="a7fcd-457">**Совместная работа стала проще.** Улучшенные возможности совместного редактирования означают, что при работе с условным форматированием, стилями ячеек и т. д. изменения, внесенные вами, легко объединяются с изменениями, внесенными другими участниками совместной работы.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-457">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="a7fcd-458">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-458">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a7fcd-459">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-459">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="a7fcd-460">Набор Office. Обновления функций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-460">Office Suite Feature updates:</span></span>

- <span data-ttu-id="a7fcd-461">**Новые значки приложений Office.** Обновленные значки приложений отражают простоту, функциональность и интеллектуальные возможности Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-461">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="a7fcd-462">Обновления функций Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-462">Outlook Feature updates:</span></span>

- <span data-ttu-id="a7fcd-463">**Расширенная защита от атак.** Система Office 365 Advanced Threat Protection защищает от атак с помощью гиперссылок в электронных письмах, вложенных и подписанных сообщениях, сетевых путях и т. д.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-463">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="a7fcd-464">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-464">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a7fcd-465">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-465">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a7fcd-466">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-466">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a7fcd-467">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-467">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a7fcd-468">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-468">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="a7fcd-469">Обновления функций Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-469">Word Feature updates:</span></span>

- <span data-ttu-id="a7fcd-470">**Другие люди быстрее увидят сделанные вами изменения.** Улучшенные функции совместного редактирования означают, что участники совместной работы смогут просматривать сделанные вами изменения быстрее, чем когда-либо раньше.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-470">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="a7fcd-471">**Наслаждайтесь поиском.** Чтобы упростить поиск нужного значка, была добавлена функция "Поиск" к пункту "Вставка значков".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-471">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a7fcd-472">Кнопка "Вставить" помогает узнать, сколько значков было выбрано.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-472">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a7fcd-473">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-473">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-474">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-474">Outlook</span></span>

- <div><span data-ttu-id="a7fcd-475"><span>Исправлена проблема, из-за которой получатели приглашения на собрание получали два уведомления после отмены собрания</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-475"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a7fcd-476">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-476">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-477"><span>Исправлена проблема, которая приводила к сбою, когда пользователь выбирал пункт "Без контура" или "Без заливки" в меню "Фигуры и значки"</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-477"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="a7fcd-478">**2 августа 2019 г.**</span><span class="sxs-lookup"><span data-stu-id="a7fcd-478">**August 02, 2019**</span></span><br/>
<span data-ttu-id="a7fcd-479">Версия 1908 (сборка 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-479">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="a7fcd-480">Обновления функций Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-480">Excel Feature updates:</span></span>

- <span data-ttu-id="a7fcd-481">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-481">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a7fcd-482">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-482">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="a7fcd-483">Обновления функций Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-483">Outlook Feature updates:</span></span>

- <span data-ttu-id="a7fcd-484">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-484">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a7fcd-485">Обновления функций PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-485">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a7fcd-486">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-486">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a7fcd-487">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-487">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="a7fcd-488">Обновления функций Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-488">Word Feature updates:</span></span>

- <span data-ttu-id="a7fcd-489">**Преобразование файлов для улучшения доступности.** Обновите свои файлы до современного формата, чтобы сделать их доступнее для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-489">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a7fcd-490">**Выразите мысль другими словами.** Если вы хотите выразить мысль по-другому, можно воспользоваться функцией переписывания.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-490">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="a7fcd-491">Она предлагает другие варианты, подходящие для ваших фраз.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-491">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="a7fcd-492">**Применение меток конфиденциальности к документам.** Применяйте метки конфиденциальности к своим файлам и сообщениям электронной почты, чтобы они соответствовали политикам защиты данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-492">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a7fcd-493">Обновления, не связанные с безопасностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-493">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-494">Доступ</span><span class="sxs-lookup"><span data-stu-id="a7fcd-494">Access</span></span>
- <span data-ttu-id="a7fcd-495">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-495">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-496">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-496">Excel</span></span>

- <div><span data-ttu-id="a7fcd-497"><span>Устранена проблема, из-за которой при печати PDF-файлов применялась команда &quot;Повторять все подписи&quot;</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-497"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="a7fcd-498">Набор приложений Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-498">Office Suite</span></span>

- <div><span data-ttu-id="a7fcd-499"><span>Устранена проблема, из-за которой документ иногда не открывался с рабочего стола</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-499"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="a7fcd-500"><span>Устранена проблема с обновлением при получении неправильного сообщения об ошибке &quot;Выполняется другая установка&quot;</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-500"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="a7fcd-501"><span>Устранена проблема, из-за которой появлялись сообщения об ошибке при установке обновлений для системы безопасности</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-501"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="a7fcd-502"><span>Устранена проблема, из-за которой иногда исчезал курсор</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-502"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="a7fcd-503"><span>Устранена проблема, из-за которой по умолчанию открывалась вкладка "Рисование" вместо вкладки "Главная"</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-503"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="a7fcd-504"><span>Устранена проблема, из-за которой представление в виде большого дерева могло привести к сбою</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-504"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="a7fcd-505">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-505">Outlook</span></span>

- <div></div><span data-ttu-id="a7fcd-506"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Устранена проблема, при которой многократно отображался запрос пароля</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-506"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="a7fcd-507"><span>Устранена проблема, из-за которой создавался неправильный запрос адреса электронной почты</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-507"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="a7fcd-508"><span>Устранена проблема, из-за которой не открывались элементы календаря, созданные в устаревших версиях Outlook</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-508"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-509">PowerPoint</span></span>

- <div><span data-ttu-id="a7fcd-510"><span>Устранена проблема, из-за которой не запускались некоторые анимации</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-510"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a7fcd-511">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-511">Project</span></span>
- <span data-ttu-id="a7fcd-512">Устранение проблем с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="a7fcd-512">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-513">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-513">Word</span></span>

- <div><span data-ttu-id="a7fcd-514"><span>Устранена проблема, из-за которой ответы на комментарии отображались не по порядку</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-514"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="a7fcd-515"><span>Устранена проблема, из-за которой в некоторых ситуациях вместо комментариев отображались подсказки</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-515"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="a7fcd-516"><span>Устранена проблема, из-за которой при попытке добавить комментарий отображалась область исправлений</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-516"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="a7fcd-517"><span>Устранена проблема, из-за которой не отображался раскрывающийся список отмены</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-517"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="a7fcd-518"><span>Устранена проблема, из-за которой не удавалось добавить комментарии</span></span><span class="sxs-lookup"><span data-stu-id="a7fcd-518"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="a7fcd-519">26 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-519">July 26, 2019</span></span>
<span data-ttu-id="a7fcd-520">Версия 1908 (сборка 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-520">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-521">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-521">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="a7fcd-522">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-522">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="a7fcd-523">Создание более удобных для чтения PDF-документов</span><span class="sxs-lookup"><span data-stu-id="a7fcd-523">Create more accessible PDFs</span></span>

<span data-ttu-id="a7fcd-524">Создайте PDF-файл, и средство проверки читаемости укажет на проблемы с читаемостью для их устранения перед сохранением.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-524">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-525">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-525">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-526">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-526">All</span></span>

- <span data-ttu-id="a7fcd-527">Исправлена проблема, из-за которой при обновлении Office иногда могли возникать ошибки с сопоставлением типов файлов и значками для Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-527">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-528">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-528">Word</span></span> 
- <span data-ttu-id="a7fcd-529">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-529">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-530">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-530">Excel</span></span>
- <span data-ttu-id="a7fcd-531">Исправлена проблема, из-за которой перемещение диаграммы иногда могло приводить к сбою</span><span class="sxs-lookup"><span data-stu-id="a7fcd-531">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="a7fcd-532">Исправлена проблема, из-за которой получение объекта Workbook из объекта Chart после изменения типов диаграмм иногда могло приводить к ошибке</span><span class="sxs-lookup"><span data-stu-id="a7fcd-532">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-533">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-534">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-534">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-535">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-535">Outlook</span></span>
- <span data-ttu-id="a7fcd-536">Исправлена проблема, из-за которой на упрощенной ленте отключенный элемент управления иногда не затенялся</span><span class="sxs-lookup"><span data-stu-id="a7fcd-536">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-537">Доступ</span><span class="sxs-lookup"><span data-stu-id="a7fcd-537">Access</span></span>
- <span data-ttu-id="a7fcd-538">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-538">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-539">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-539">Project</span></span>
- <span data-ttu-id="a7fcd-540">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-540">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="a7fcd-541">19 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-541">July 19, 2019</span></span>
<span data-ttu-id="a7fcd-542">Версия 1908 (сборка 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-542">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-543">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-543">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-544">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-544">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="a7fcd-545">Изучение значения сокращений при чтении в Word Online</span><span class="sxs-lookup"><span data-stu-id="a7fcd-545">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="a7fcd-546">Когда вам попадется сокращение, мы попробуем расшифровать его с помощью данных вашей организации.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-546">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-547">Важные исправления</span><span class="sxs-lookup"><span data-stu-id="a7fcd-547">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-548">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-548">Word</span></span> 
- <span data-ttu-id="a7fcd-549">Исправлена проблема с отсутствием тега BookMarkEnd.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-549">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="a7fcd-550">Исправлена проблема с изменением выбранного шрифта при вводе пользователем специальных символов.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-550">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="a7fcd-551">Исправлена проблема, из-за которой в новой карточке с комментариями иногда могли появляться пустые ответы.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-551">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="a7fcd-552">Исправлена проблема с потерей форматирования при общем доступе к электронной почте.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-552">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-553">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-553">Excel</span></span>
- <span data-ttu-id="a7fcd-554">Исправлена проблема, из-за которой массив с большим диапазоном иногда мог вызывать сбой.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-554">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="a7fcd-555">Значительно улучшена производительность при копировании данных из отфильтрованных диапазонов.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-555">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="a7fcd-556">Исправлена проблема, из-за которой некоторые файлы с именами, содержавшими специальные символы, не открывались.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-556">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-557">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-558">Исправлена проблема, из-за которой не присваивалось название раздела вновь созданному разделу в PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-558">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="a7fcd-559">Исправлена проблема, из-за которой использование пользовательского интерфейса затруднялось при использовании монитора 4:3.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-559">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-560">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-560">Outlook</span></span>
- <span data-ttu-id="a7fcd-561">Исправлена проблема, из-за которой доступные помещения могли не отображаться в списке.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-561">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="a7fcd-562">Исправлена проблема, из-за которой форматирование HTML для некоторых пользователей POP3 было недоступным.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-562">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-563">Доступ</span><span class="sxs-lookup"><span data-stu-id="a7fcd-563">Access</span></span>
- <span data-ttu-id="a7fcd-564">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-564">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-565">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-565">Project</span></span>
- <span data-ttu-id="a7fcd-566">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-566">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="a7fcd-567">12 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-567">July 12, 2019</span></span>
<span data-ttu-id="a7fcd-568">Версия 1907 (сборка 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-568">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-569">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-569">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-570">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-570">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="a7fcd-571">Воспроизведение рукописного ввода в презентациях</span><span class="sxs-lookup"><span data-stu-id="a7fcd-571">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="a7fcd-572">Используйте анимацию воспроизведения для рукописного ввода в PowerPoint для большей наглядности презентаций.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-572">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-573">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-573">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-574">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-574">Word</span></span> 
- <span data-ttu-id="a7fcd-575">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-575">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-576">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-576">Excel</span></span>
- <span data-ttu-id="a7fcd-577">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-577">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-578">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-578">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-579">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-579">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-580">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-580">Outlook</span></span>
- <span data-ttu-id="a7fcd-581">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-581">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-582">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-582">Access</span></span>
- <span data-ttu-id="a7fcd-583">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-583">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-584">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-584">Project</span></span>
- <span data-ttu-id="a7fcd-585">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-585">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="a7fcd-586">5 июля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-586">July 5, 2019</span></span>
<span data-ttu-id="a7fcd-587">Версия 1907 (сборка 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-587">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-588">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-588">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="a7fcd-589">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-589">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="a7fcd-590">Фигуры в виде эскиза!</span><span class="sxs-lookup"><span data-stu-id="a7fcd-590">Sketchy Shapes!</span></span>

<span data-ttu-id="a7fcd-591">Находитесь в процессе создания презентации?</span><span class="sxs-lookup"><span data-stu-id="a7fcd-591">In the middle of drafting a presentation?</span></span> <span data-ttu-id="a7fcd-592">Примените эскизный стиль, чтобы продемонстрировать незавершенность работы.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-592">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="a7fcd-593">Это придает индивидуальность вашим объектам, не превращая их в фигуры произвольной формы, нарисованные от руки.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-593">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-594">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-594">Excel</span></span>

- <span data-ttu-id="a7fcd-595">**Быстрое предоставление общего доступа к файлам**. Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-595">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a7fcd-596">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-596">PowerPoint</span></span>

- <span data-ttu-id="a7fcd-597">**Параметр "Печать номеров слайдов на раздаточных материалах" перемещен в меню печати для облегчения доступа.** Он находится в раскрывающемся меню "Печать > Макет печати", когда выбран макет раздаточных материалов.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-597">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="a7fcd-598">Это также позволяет легко включать и отключать этот параметр для отдельных презентаций.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-598">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="a7fcd-599">Подробнее</span><span class="sxs-lookup"><span data-stu-id="a7fcd-599">Learn more</span></span>](https://support.office.com/ru-RU/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="a7fcd-600">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-600">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-601">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-601">Word</span></span>

- <span data-ttu-id="a7fcd-602">**Быстрое предоставление общего доступа к файлам.** Делитесь своими документами прямо из списка недавно использовавшихся файлов, не открывая их.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-602">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-603">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-603">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-604">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-604">All</span></span>
- <span data-ttu-id="a7fcd-605">Значительно улучшена производительность подсказок ленты</span><span class="sxs-lookup"><span data-stu-id="a7fcd-605">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="a7fcd-606">Исправлена проблема, мешавшая правильному отображению диалогового окна "Посмотрите, что нового появится в ближайшее время"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-606">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="a7fcd-607">Исправлена проблема, которая могла приводить к неправильному выравниванию фотографий во всплывающей коллекции совместной работы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-607">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-608">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-608">Word</span></span> 
- <span data-ttu-id="a7fcd-609">Исправлена проблема, которая иногда могла препятствовать добавлению новых примечаний</span><span class="sxs-lookup"><span data-stu-id="a7fcd-609">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="a7fcd-610">Исправлена проблема, из-за которой таблицы иногда могли вызывать сбой</span><span class="sxs-lookup"><span data-stu-id="a7fcd-610">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="a7fcd-611">Исправлена проблема, из-за которой иногда могли добавляться недопустимые данные в конец слияния почты</span><span class="sxs-lookup"><span data-stu-id="a7fcd-611">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="a7fcd-612">Исправлена проблема, которая могла приводить к неправильному отображению некоторых уравнений LaTeX</span><span class="sxs-lookup"><span data-stu-id="a7fcd-612">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-613">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-613">Excel</span></span>
- <span data-ttu-id="a7fcd-614">Исправлена проблема, из-за которой изменение типов диаграмм могло иногда приводить к возникновению исключения во время выполнения</span><span class="sxs-lookup"><span data-stu-id="a7fcd-614">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="a7fcd-615">Исправлена проблема с отображением неправильной ленты при открытии нескольких окон</span><span class="sxs-lookup"><span data-stu-id="a7fcd-615">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="a7fcd-616">Исправлена проблема, которая могла вызывать ошибку при открытии макросом второго экземпляра книги</span><span class="sxs-lookup"><span data-stu-id="a7fcd-616">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="a7fcd-617">Исправлена проблема, которая могла приводить к сбою при открытии книги, создании книги или переключении между книгами</span><span class="sxs-lookup"><span data-stu-id="a7fcd-617">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="a7fcd-618">Исправлена проблема, не позволявшая пользователям открыть PDF-файл, созданный из Word в Teams</span><span class="sxs-lookup"><span data-stu-id="a7fcd-618">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-619">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-620">Исправлена проблема, из-за которой могло ухудшаться качество диаграммы при экспорте в PDF-файл</span><span class="sxs-lookup"><span data-stu-id="a7fcd-620">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="a7fcd-621">Исправлена проблема, препятствовавшая отображению подсказки с указанием расстояния до центра</span><span class="sxs-lookup"><span data-stu-id="a7fcd-621">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-622">Outlook</span></span>
- <span data-ttu-id="a7fcd-623">Исправлена проблема, которая иногда могла мешать отображению ошибки с сообщением о переполнении диска</span><span class="sxs-lookup"><span data-stu-id="a7fcd-623">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="a7fcd-624">Исправлена проблема, которая могла приводить к дублированию вложений при обновлении приглашения на собрание</span><span class="sxs-lookup"><span data-stu-id="a7fcd-624">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-625">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-625">Access</span></span>
- <span data-ttu-id="a7fcd-626">Исправлена проблема, препятствовавшая возврату длинных целых значений при некоторых запросах</span><span class="sxs-lookup"><span data-stu-id="a7fcd-626">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="a7fcd-627">Исправлена проблема, из-за которой поле SQL могло стать нередактируемым</span><span class="sxs-lookup"><span data-stu-id="a7fcd-627">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="a7fcd-628">Исправлена проблема, из-за которой подсказки могло быть плохо видно на экранах с высоким разрешением</span><span class="sxs-lookup"><span data-stu-id="a7fcd-628">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-629">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-629">Project</span></span>
- <span data-ttu-id="a7fcd-630">Исправлена проблема, из-за которой значения флагов могли стать нередактируемыми в новых задачах</span><span class="sxs-lookup"><span data-stu-id="a7fcd-630">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="a7fcd-631">Исправлена проблема, которая могла приводить к неправильной установке фактической даты начала в назначениях и задачах при обновлении состояния</span><span class="sxs-lookup"><span data-stu-id="a7fcd-631">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="a7fcd-632">Исправлена проблема, которая могла приводить к неправильному отображению превышения доступности для некоторых ресурсов</span><span class="sxs-lookup"><span data-stu-id="a7fcd-632">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="a7fcd-633">Исправлена проблема, из-за которой метод добавления объектов TaskDependencies мог завершаться сбоем, если добавлен параметр Lag, десятичным разделителем является запятая и выполнено подключение к серверу</span><span class="sxs-lookup"><span data-stu-id="a7fcd-633">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="a7fcd-634">Исправлена проблема, из-за которой обновление значений таблицы подстановки локальных настраиваемых полей через CSOM могло приводить к сбою компьютеров</span><span class="sxs-lookup"><span data-stu-id="a7fcd-634">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="a7fcd-635">Исправлена проблема, из-за которой значения общего объема работ могли отображаться неправильно, если они содержали десятичное число</span><span class="sxs-lookup"><span data-stu-id="a7fcd-635">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="a7fcd-636">28 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-636">June 28, 2019</span></span>
<span data-ttu-id="a7fcd-637">Версия 1907 (сборка 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-637">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-638">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-638">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-639">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-639">Excel</span></span>

- <span data-ttu-id="a7fcd-640">**Быстрое кодирование с дополнительными возможностями Power Query.** Быстрое завершение кода с помощью автозаполнения и выделения синтаксиса цветом.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-640">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="a7fcd-641">Также легко находить функции, столбцы и параметры</span><span class="sxs-lookup"><span data-stu-id="a7fcd-641">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="a7fcd-642">**Объединение таблиц по похожим столбцам.** Команда "Получить и преобразовать" (Power Query) теперь включает логику приблизительного сопоставления текста (поиска нечетких соответствий) при сравнении столбцов для слияния таблиц.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-642">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-643">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-643">Word</span></span>

- <span data-ttu-id="a7fcd-644">**Улучшенные возможности совместного редактирования.** Повышена надежность при совместном редактировании.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-644">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="a7fcd-645">Word, Excel, PowerPoint и Visio</span><span class="sxs-lookup"><span data-stu-id="a7fcd-645">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="a7fcd-646">Рекомендуемые документы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-646">Recommended Documents</span></span>

<span data-ttu-id="a7fcd-647">Находите рекомендуемые вам документы с важными действиями.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-647">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-648">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-648">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-649">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-649">Word</span></span> 
- <span data-ttu-id="a7fcd-650">Исправлена проблема, из-за которой не удавалось открыть некоторые DOC-файлы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-650">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="a7fcd-651">Исправлена проблема, которая могла мешать правильной загрузке примечаний</span><span class="sxs-lookup"><span data-stu-id="a7fcd-651">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-652">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-652">Excel</span></span>
- <span data-ttu-id="a7fcd-653">Улучшена производительность запросов Power Query</span><span class="sxs-lookup"><span data-stu-id="a7fcd-653">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-654">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-654">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-655">Исправлена проблема, связанная с использованием пера на устройстве Surface, которая могла приводить к мерцанию экрана</span><span class="sxs-lookup"><span data-stu-id="a7fcd-655">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-656">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-656">Outlook</span></span>
- <span data-ttu-id="a7fcd-657">Исправлена проблема, из-за которой могло изменяться состояние доступности встречи при преобразовании в собрание</span><span class="sxs-lookup"><span data-stu-id="a7fcd-657">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="a7fcd-658">Исправлена проблема с отображением неправильного шаблона и описания, если сообщение защищено с помощью специального шаблона</span><span class="sxs-lookup"><span data-stu-id="a7fcd-658">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-659">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-659">Access</span></span>
- <span data-ttu-id="a7fcd-660">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-660">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-661">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-661">Project</span></span>
- <span data-ttu-id="a7fcd-662">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-662">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="a7fcd-663">21 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-663">June 21, 2019</span></span>
<span data-ttu-id="a7fcd-664">Версия 1907 (сборка 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-664">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-665">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-665">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-666">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-666">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="a7fcd-667">Темный режим для черной темы в классическом приложении Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-667">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="a7fcd-668">Когда используется темный режим, для пользователей, выбравших черную тему, области чтения и создания сообщений теперь также отображаются на темном фоне при чтении и создании сообщений электронной почты соответственно.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-668">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="a7fcd-669">В области чтения и на ленте есть переключатель с изображением солнца или луны, позволяющий пользователям предварительно просмотреть сообщение на светлом фоне.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-669">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-670">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-670">Getting Started:</span></span>

1. <span data-ttu-id="a7fcd-671">Включите черную тему, и темный режим запустится по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-671">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="a7fcd-672">Используйте переключатель с изображением луны или солнца (в области чтения и на ленте), чтобы просмотреть оформление сообщения для пользователей, не применяющих темный режим</span><span class="sxs-lookup"><span data-stu-id="a7fcd-672">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-673">Возможные действия</span><span class="sxs-lookup"><span data-stu-id="a7fcd-673">Scenarios to Try</span></span>

1. <span data-ttu-id="a7fcd-674">Читайте сообщения в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-674">Read emails in dark mode.</span></span> <span data-ttu-id="a7fcd-675">Если вам не удается что-то прочитать, используйте переключатель с изображением солнца в области чтения, чтобы переключиться на светлый фон.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-675">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="a7fcd-676">Создавайте сообщения в темном режиме.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-676">Compose emails in dark mode.</span></span> <span data-ttu-id="a7fcd-677">Просматривайте сообщение на светлом фоне с помощью переключателя с изображением солнца на ленте.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-677">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="a7fcd-678">Если вы столкнулись с неправильным отображением сообщений, отправьте их (в виде вложения) на адрес электронной почты OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="a7fcd-678">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="a7fcd-679">Получение предложений по расположению</span><span class="sxs-lookup"><span data-stu-id="a7fcd-679">Get location suggestions</span></span>

<span data-ttu-id="a7fcd-680">Начните ввод текста и Outlook подберет подходящие расположения.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-680">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="a7fcd-681">Это применяется к полю "Расположение" при создании встреч и собраний.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-681">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-682">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-682">Getting Started:</span></span>

- <span data-ttu-id="a7fcd-683">Создайте встречу или собрание в календаре Outlook в Office 365 или Outlook.com.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-683">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="a7fcd-684">Щелкните поле "Расположение" и начните вводить текст...</span><span class="sxs-lookup"><span data-stu-id="a7fcd-684">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-685">Возможные действия</span><span class="sxs-lookup"><span data-stu-id="a7fcd-685">Scenarios to Try</span></span>

<span data-ttu-id="a7fcd-686">При добавлении конференц-зала к собранию щелкните поле "Расположение", а не надстройку "Поиск помещений" или адресную книгу.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-686">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="a7fcd-687">Для встреч в общественных местах, например в ресторане, кафе или даже кабинете стоматолога, постарайтесь найти точное расположение с помощью нового средства выбора.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-687">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="a7fcd-688">Так вы сможете получать уведомления в Outlook Mobile, когда придет время отправляться в путь.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-688">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-689">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-689">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-690">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-690">All</span></span>
- <span data-ttu-id="a7fcd-691">Исправлена проблема, из-за которой поле поиска могло оставаться активным в автономном режиме</span><span class="sxs-lookup"><span data-stu-id="a7fcd-691">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-692">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-692">Word</span></span> 
- <span data-ttu-id="a7fcd-693">Исправлена проблема, из-за которой иногда трудно было увидеть фокус клавиатуры</span><span class="sxs-lookup"><span data-stu-id="a7fcd-693">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="a7fcd-694">Исправлена проблема, из-за которой текст, вставлявшийся в новый документ, иногда мог выравниваться неправильно</span><span class="sxs-lookup"><span data-stu-id="a7fcd-694">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="a7fcd-695">Исправлена проблема, из-за которой некоторым пользователям не удавалось сохранять изменения после приостановки работы компьютера</span><span class="sxs-lookup"><span data-stu-id="a7fcd-695">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="a7fcd-696">Исправлена проблема, из-за которой в некоторых случаях печатался весь документ вместо выбранного диапазона</span><span class="sxs-lookup"><span data-stu-id="a7fcd-696">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="a7fcd-697">Исправлена проблема, которая могла затруднять чтение примечаний на небольших экранах</span><span class="sxs-lookup"><span data-stu-id="a7fcd-697">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="a7fcd-698">Исправлена проблема, которая могла приводить к сбою при записи на устройство</span><span class="sxs-lookup"><span data-stu-id="a7fcd-698">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-699">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-699">Excel</span></span>
- <span data-ttu-id="a7fcd-700">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-700">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-701">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-701">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-702">Исправлена проблема, из-за которой иногда трудно было увидеть фокус клавиатуры</span><span class="sxs-lookup"><span data-stu-id="a7fcd-702">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-703">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-703">Outlook</span></span>
- <span data-ttu-id="a7fcd-704">Исправлена проблема, из-за которой надстройка могла неправильно отображаться как включенная, хотя она выключена.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-704">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="a7fcd-705">Исправлена проблема, не позволявшая пользователю просматривать все политики хранения, если их много</span><span class="sxs-lookup"><span data-stu-id="a7fcd-705">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-706">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-706">Access</span></span>
- <span data-ttu-id="a7fcd-707">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-707">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-708">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-708">Project</span></span>
- <span data-ttu-id="a7fcd-709">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-709">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="a7fcd-710">14 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-710">June 14, 2019</span></span>
<span data-ttu-id="a7fcd-711">Версия 1907 (сборка 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-711">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-712">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-712">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-713">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-713">Word</span></span> 
- <span data-ttu-id="a7fcd-714">Исправлена проблема, которая могла препятствовать входу пользователя при сохранении в OneDrive</span><span class="sxs-lookup"><span data-stu-id="a7fcd-714">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="a7fcd-715">Исправлена проблема, из-за которой пользователю могло быть запрещено изменять свойства SharePoint в режиме ограниченного доступа</span><span class="sxs-lookup"><span data-stu-id="a7fcd-715">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="a7fcd-716">Исправлена проблема, из-за которой содержимое колонтитулов могло меняться при изменении полей</span><span class="sxs-lookup"><span data-stu-id="a7fcd-716">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="a7fcd-717">Исправлена проблема, из-за которой форматирование могло разрываться при переходе в веб-представление</span><span class="sxs-lookup"><span data-stu-id="a7fcd-717">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="a7fcd-718">Исправлена проблема, которая могла помешать пользователю использовать настраиваемые поля при открытии из SharePoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-718">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-719">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-719">Excel</span></span>
- <span data-ttu-id="a7fcd-720">Исправлена проблема с производительностью при удалении строк отфильтрованного набора</span><span class="sxs-lookup"><span data-stu-id="a7fcd-720">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="a7fcd-721">Исправлена проблема, которая могла иногда вызывать мерцание указателя мыши в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="a7fcd-721">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="a7fcd-722">Устранена проблема, которая могла приводить к сбою при удалении ряда</span><span class="sxs-lookup"><span data-stu-id="a7fcd-722">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="a7fcd-723">Исправлена проблема, из-за которой некоторым пользователям предоставлялась возможность добавить журнал версий, когда он недоступен</span><span class="sxs-lookup"><span data-stu-id="a7fcd-723">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="a7fcd-724">Исправлена проблема, которая могла приводить к возникновению исключения при использовании средства сравнения электронных таблиц</span><span class="sxs-lookup"><span data-stu-id="a7fcd-724">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-725">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-725">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-726">Устранена проблема, из-за которой мог происходить сбой при переходе по ссылке к SharePoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-726">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="a7fcd-727">Исправлена проблема, из-за которой пользователь мог переключаться на следующую страницу при вводе с помощью ручки Surface</span><span class="sxs-lookup"><span data-stu-id="a7fcd-727">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-728">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-728">Outlook</span></span>
- <span data-ttu-id="a7fcd-729">Исправлена проблема, из-за которой в некоторых случаях поле "Кому" отображалось увеличенным</span><span class="sxs-lookup"><span data-stu-id="a7fcd-729">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-730">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-730">Access</span></span>
- <span data-ttu-id="a7fcd-731">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-731">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-732">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-732">Project</span></span>
- <span data-ttu-id="a7fcd-733">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-733">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="a7fcd-734">7 июня 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-734">June 7, 2019</span></span>
<span data-ttu-id="a7fcd-735">Версия 1907 (сборка 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-735">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-736">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-736">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-737">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-737">Word</span></span> 
- <span data-ttu-id="a7fcd-738">Исправлена проблема, из-за которой возникал сбой в работе Word при автозамене первой буквы предложения на прописную</span><span class="sxs-lookup"><span data-stu-id="a7fcd-738">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="a7fcd-739">Улучшена производительность при редактировании документа в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-739">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="a7fcd-740">Исправлена проблема, из-за которой неправильно отображались векторные изображения, созданные в Adobe Illustrator</span><span class="sxs-lookup"><span data-stu-id="a7fcd-740">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-741">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-741">Excel</span></span>
- <span data-ttu-id="a7fcd-742">Исправлена проблема, из-за которой поля сортировки могли быть неправильно установлены при записи макроса</span><span class="sxs-lookup"><span data-stu-id="a7fcd-742">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="a7fcd-743">Исправлена проблема, приводящая к зависанию или сбою при пересчете формулы массива</span><span class="sxs-lookup"><span data-stu-id="a7fcd-743">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-744">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-744">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-745">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-745">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-746">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-746">Outlook</span></span>
- <span data-ttu-id="a7fcd-747">Исправлена проблема, из-за которой встроенные вложения иногда имели неправильный масштаб</span><span class="sxs-lookup"><span data-stu-id="a7fcd-747">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-748">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-748">Access</span></span>
- <span data-ttu-id="a7fcd-749">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-749">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-750">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-750">Project</span></span>
- <span data-ttu-id="a7fcd-751">Исправлена проблема, из-за которой в расписании заданий с фиксированной длительностью может изменяться дата окончания</span><span class="sxs-lookup"><span data-stu-id="a7fcd-751">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="a7fcd-752">Исправлена проблема, из-за которой могло неправильно отображаться значение процента выполнения при открытии проекта из более ранней версии</span><span class="sxs-lookup"><span data-stu-id="a7fcd-752">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="a7fcd-753">31 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-753">May 31, 2019</span></span>
<span data-ttu-id="a7fcd-754">Версия 1906 (сборка 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-754">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-755">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-755">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-756">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-756">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="a7fcd-757">Диалоговое окно обращения в службу поддержки теперь закрепляется и отображается справа</span><span class="sxs-lookup"><span data-stu-id="a7fcd-757">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="a7fcd-758">Диалоговое окно, используемое для обращения в службу поддержки, отображается в области справа и выводится как закрепленное окно.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-758">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="a7fcd-759">Рукописный ввод в вашем электронном письме!</span><span class="sxs-lookup"><span data-stu-id="a7fcd-759">Ink in Your Email!</span></span>

<span data-ttu-id="a7fcd-760">В сообщениях электронной почты Outlook теперь можно рисовать и создавать примечания к изображениям.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-760">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-761">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-761">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="a7fcd-762">Открытие ссылок на документы в Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-762">Open document links in Word</span></span>

<span data-ttu-id="a7fcd-763">При переходе по ссылке на документ в Office вы можете изменить параметр, чтобы открывать его в приложении Word по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-763">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="a7fcd-764">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-764">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a7fcd-765">Подробнее: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a7fcd-765">Learn more: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-766">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-766">Getting Started:</span></span>

<span data-ttu-id="a7fcd-767">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-767">Feature will default to off.</span></span> <span data-ttu-id="a7fcd-768">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-768">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a7fcd-769">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-769">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a7fcd-770">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-770">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a7fcd-771">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-771">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a7fcd-772">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-772">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-773">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-773">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-774">Чтобы запустить интерфейс согласия на открытие ссылки на документ Word, хранящийся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-774">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a7fcd-775">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-775">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-776">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-776">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="a7fcd-777">Открытие ссылок на презентации в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-777">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="a7fcd-778">При переходе по ссылке на презентацию в Office вы можете изменить параметр, чтобы открывать ее в приложении PowerPoint по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-778">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="a7fcd-779">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-779">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a7fcd-780">Подробнее: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a7fcd-780">Learn more: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-781">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-781">Getting Started:</span></span>

<span data-ttu-id="a7fcd-782">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-782">Feature will default to off.</span></span> <span data-ttu-id="a7fcd-783">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-783">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a7fcd-784">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-784">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a7fcd-785">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-785">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a7fcd-786">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-786">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a7fcd-787">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-787">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-788">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-788">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-789">Чтобы запустить интерфейс согласия на открытие ссылки на презентацию PowerPoint, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-789">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a7fcd-790">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-790">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-791">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-791">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="a7fcd-792">Открытие ссылок на книги в Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-792">Open workbook links in Excel</span></span>

<span data-ttu-id="a7fcd-793">При переходе по ссылке на книгу в Office вы можете изменить параметр, чтобы открывать ее в приложении Excel по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-793">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="a7fcd-794">Чтобы изменить параметр, выберите "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-794">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a7fcd-795">Подробнее: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a7fcd-795">Learn More: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-796">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-796">Getting Started:</span></span>

<span data-ttu-id="a7fcd-797">Функция отключена по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-797">Feature will default to off.</span></span> <span data-ttu-id="a7fcd-798">Пользователи могут включить ее с помощью параметра "Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок" или приложений WXP Win32 при появлении в них соответствующего интерфейса.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-798">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a7fcd-799">Когда пользователи переходят по ссылкам к файлам Word, PowerPoint или Excel, хранящимся в OneDrive, OneDrive для бизнеса или SharePoint, из Outlook, Word, PowerPoint или Excel, эти ссылки открываются в соответствующем приложении Office, а не в браузере по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-799">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a7fcd-800">Чтобы изменить это поведение по умолчанию, пользователи могут обновить следующий параметр в Outlook, Word, Excel и PowerPoint:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-800">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a7fcd-801">"Файл"->"Параметры"->"Дополнительно"->"Обработка ссылок"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-801">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a7fcd-802">Этот параметр доступен в Outlook, Word, PowerPoint и Excel, и его можно настроить в любом из этих приложений.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-802">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-803">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-803">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-804">Чтобы запустить интерфейс согласия на открытие ссылки на книгу Excel, хранящуюся в OneDrive или SharePoint, из Outlook, Word, PowerPoint или Excel, щелкните в Office Online пункт открытия в клиенте дважды в течение 30 дней.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-804">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a7fcd-805">После вашего согласия ссылки по умолчанию будут открываться в приложениях Win32.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-805">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-806">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-806">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-807">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-807">All</span></span>
- <span data-ttu-id="a7fcd-808">Исправлена проблема, из-за которой файлы иногда автоматически сохранялись даже при отключенной функции автоматического сохранения.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-808">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-809">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-809">Word</span></span> 
- <span data-ttu-id="a7fcd-810">Исправлена ошибка, которая могла не позволять некоторым пользователям сохранять файлы в SharePoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-810">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-811">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-811">Excel</span></span>
- <span data-ttu-id="a7fcd-812">Исправлена проблема с возможным отображением неправильного значка для неактивных фильтров</span><span class="sxs-lookup"><span data-stu-id="a7fcd-812">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-813">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-814">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-814">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-815">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-815">Outlook</span></span>
- <span data-ttu-id="a7fcd-816">Исправлена проблема, из-за которой состояние некоторых пользователей неправильно отображалось как "Не в сети" в представлении расписания группы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-816">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="a7fcd-817">Исправлена проблема, не позволявшая функции безопасных ссылок анализировать URL-адрес с конечным пробелом</span><span class="sxs-lookup"><span data-stu-id="a7fcd-817">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="a7fcd-818">Устранена проблема, из-за которой помещения отображались доступными за пределами нерабочего времени</span><span class="sxs-lookup"><span data-stu-id="a7fcd-818">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-819">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-819">Access</span></span>
- <span data-ttu-id="a7fcd-820">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-820">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-821">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-821">Project</span></span>
- <span data-ttu-id="a7fcd-822">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-822">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="a7fcd-823">24 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-823">May 24, 2019</span></span>
<span data-ttu-id="a7fcd-824">Версия 1906 (сборка 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-824">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-825">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-825">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="a7fcd-826">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="a7fcd-826">User Experience Updates</span></span>

<span data-ttu-id="a7fcd-827">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-827">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-828">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-828">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-829">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-829">All</span></span>

- <span data-ttu-id="a7fcd-830">Исправлена проблема, из-за которой не отображалась область чата</span><span class="sxs-lookup"><span data-stu-id="a7fcd-830">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-831">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-831">Word</span></span> 
- <span data-ttu-id="a7fcd-832">Исправлена проблема, из-за которой в некоторых случаях приложение Word могло неправильно выделять текст на наличие грамматических ошибок</span><span class="sxs-lookup"><span data-stu-id="a7fcd-832">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-833">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-833">Excel</span></span>
- <span data-ttu-id="a7fcd-834">Исправлена проблема, из-за которой применялся неправильный значок для элементов диаграммы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-834">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="a7fcd-835">Исправлена проблема, приводившая к активации неверной книги в скрипте VBA, если эта книга уже открыта</span><span class="sxs-lookup"><span data-stu-id="a7fcd-835">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-836">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-836">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-837">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-837">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-838">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-838">Outlook</span></span>
- <span data-ttu-id="a7fcd-839">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-839">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-840">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-840">Access</span></span>
- <span data-ttu-id="a7fcd-841">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-841">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-842">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-842">Project</span></span>
- <span data-ttu-id="a7fcd-843">Устранена ошибка, при которой приложение Project аварийно завершало работу после перехода на панель задач</span><span class="sxs-lookup"><span data-stu-id="a7fcd-843">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="a7fcd-844">17 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-844">May 17, 2019</span></span>
<span data-ttu-id="a7fcd-845">Версия 1906 (сборка 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-845">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-846">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-846">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-847">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-847">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="a7fcd-848">Обновления интерфейса пользователя</span><span class="sxs-lookup"><span data-stu-id="a7fcd-848">User Experience Updates</span></span>

<span data-ttu-id="a7fcd-849">Выпущены ожидавшиеся обновления, включая упрощенную ленту и визуальное изменение области папок, списка сообщений и области чтения.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-849">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-850">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-850">Getting Started:</span></span>

<span data-ttu-id="a7fcd-851">Эти изменения относятся к новому стандартному пользовательскому интерфейсу; он был доступен с помощью переключателя "Ожидается в ближайшее время" с середины декабря для 100 % рабочих сред</span><span class="sxs-lookup"><span data-stu-id="a7fcd-851">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="a7fcd-852">Настраиваемая упрощенная лента</span><span class="sxs-lookup"><span data-stu-id="a7fcd-852">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="a7fcd-853">Возможность простой настройки для переключения между классическим и упрощенным представлением, а также для закрепления и открепления команд.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-853">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-854">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-854">Getting Started:</span></span>

<span data-ttu-id="a7fcd-855">Пользователи могут перейти к упрощенной ленте, включив переключатель "Ожидается в ближайшее время" (изначально) и щелкнув шеврон на ленте, чтобы переключаться между классической многострочной и новой упрощенной однострочной лентой.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-855">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-856">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-856">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-857">Переключение с классической на упрощенную ленту</span><span class="sxs-lookup"><span data-stu-id="a7fcd-857">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="a7fcd-858">Выбор избранного действия</span><span class="sxs-lookup"><span data-stu-id="a7fcd-858">Pick your favorite action</span></span>

<span data-ttu-id="a7fcd-859">Не используете действия "Пометить" и "Удалить"?</span><span class="sxs-lookup"><span data-stu-id="a7fcd-859">Don't use Flag and Delete?</span></span> <span data-ttu-id="a7fcd-860">Что насчет "Архивировать" и "Пометить как прочитанные"?</span><span class="sxs-lookup"><span data-stu-id="a7fcd-860">How about Archive or Mark as Read?</span></span> <span data-ttu-id="a7fcd-861">Настройте меню быстрых действий с помощью команд, используемых чаще всего.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-861">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-862">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-862">Getting Started:</span></span>

<span data-ttu-id="a7fcd-863">Чтобы выбрать быстрые действия, щелкните правой кнопкой мыши сообщение в списке для отображения контекстного меню.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-863">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="a7fcd-864">Затем выберите пункт "Задать быстрые действия"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-864">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-865">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-865">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-866">Изменение используемых по умолчанию действий "Пометить" и "Удалить" на "Архивировать", "Переместить", "Пометить как прочитанные" или "Отсутствует" для уменьшения элементов в списке сообщений</span><span class="sxs-lookup"><span data-stu-id="a7fcd-866">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="a7fcd-867">Выбор свободного или компактного макета</span><span class="sxs-lookup"><span data-stu-id="a7fcd-867">Relaxed or tighter layout?</span></span> <span data-ttu-id="a7fcd-868">по своему усмотрению</span><span class="sxs-lookup"><span data-stu-id="a7fcd-868">You choose</span></span>

<span data-ttu-id="a7fcd-869">С помощью компактных интервалов можно выбрать дополнительное пространство между элементами или более сжатый макет, чтобы увидеть больше элементов.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-869">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-870">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-870">Getting Started:</span></span>

<span data-ttu-id="a7fcd-871">Вкладка "Вид", флажок "Уменьшить интервал" в группе "Сообщения" для классической ленты и параметры текущего представления для упрощенной ленты</span><span class="sxs-lookup"><span data-stu-id="a7fcd-871">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-872">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-872">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-873">Использование Outlook для просмотра и создания сообщений с включенным и отключенным параметром.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-873">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="a7fcd-874">При включенном параметре "Уменьшить интервал" на странице располагается больше сообщений, а элементы управления в формах создания упрощаются.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-874">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="a7fcd-875">Дедупликация недавно использовавшихся записей при применении клиента синхронизации OneDrive</span><span class="sxs-lookup"><span data-stu-id="a7fcd-875">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="a7fcd-876">Улучшите интеграцию с клиентом синхронизации OneDrive с помощью облачных вложений, выполнив дедупликацмию недавно использовавшихся записей, обеспечивающую ускорение вложения в виде копии для синхронизированных данных</span><span class="sxs-lookup"><span data-stu-id="a7fcd-876">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-877">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-877">Getting Started:</span></span>

<span data-ttu-id="a7fcd-878">При использовании клиента синхронизации OneDrive дубликаты больше не отображаются в меню последних выбиравшихся для вложений файлов.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-878">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-879">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-879">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-880">Включение клиента синхронизации OneDrive и использование меню "Вложить файл" в классической версии Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-880">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="a7fcd-881">Улучшенная синхронизация общих папок для почтовых ящиков с большим числом папок</span><span class="sxs-lookup"><span data-stu-id="a7fcd-881">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="a7fcd-882">В течение нескольких лет при синхронизации общих почтовых ящиков в приложении Outlook существовало ограничение не более 500 папок.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-882">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="a7fcd-883">В результате этого изменения при синхронизации в Outlook больше не будет применяться это ограничение в 500 папок.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-883">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-884">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-884">Getting Started:</span></span>

<span data-ttu-id="a7fcd-885">Создайте в почтовом ящике 1000 папок, предоставьте другому пользователю доступ к почтовому ящику, создайте профиль Outlook для "другого пользователя" и убедитесь в выполнении синхронизации.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-885">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-886">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-886">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="a7fcd-887">Стереть лишь небольшую часть</span><span class="sxs-lookup"><span data-stu-id="a7fcd-887">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-888">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-888">Getting Started:</span></span>

<span data-ttu-id="a7fcd-889">Откройте вкладку "Рисование". Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-889">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="a7fcd-890">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-890">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-891">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-891">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-892">Откройте вкладку "Рисование". Выберите перо.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-892">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="a7fcd-893">Нанесите росчерк пером.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-893">Draw an ink stroke.</span></span> <span data-ttu-id="a7fcd-894">Выберите раскрывающееся меню "Ластик".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-894">Select the Eraser dropdown.</span></span> <span data-ttu-id="a7fcd-895">Выберите маленький или средний ластик.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-895">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="a7fcd-896">Сотрите лишь небольшую часть росчерка пера.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-896">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-897">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-897">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-898">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-898">All</span></span> 
- <span data-ttu-id="a7fcd-899">Исправлена проблема, из-за которой некоторым пользователям могло не удаваться сохранять файлы в формате PDF</span><span class="sxs-lookup"><span data-stu-id="a7fcd-899">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="a7fcd-900">Исправлена проблема, которая могла влиять на сохранение пользователями больших файлов в 32-разрядной системе</span><span class="sxs-lookup"><span data-stu-id="a7fcd-900">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-901">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-901">Word</span></span> 
- <span data-ttu-id="a7fcd-902">Значительно повышена скорость реагирования функции диктовки</span><span class="sxs-lookup"><span data-stu-id="a7fcd-902">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-903">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-903">Excel</span></span>
- <span data-ttu-id="a7fcd-904">Исправлена проблема, из-за которой события двойного щелчка могли не срабатывать на устройствах с сенсорным экраном</span><span class="sxs-lookup"><span data-stu-id="a7fcd-904">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="a7fcd-905">Исправлена проблема, которая могла блокировать для некоторых пользователей редактирование макросов VBA</span><span class="sxs-lookup"><span data-stu-id="a7fcd-905">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="a7fcd-906">Исправлена проблема, которая могла влиять на производительность при использовании срезов</span><span class="sxs-lookup"><span data-stu-id="a7fcd-906">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-907">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-907">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-908">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-908">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-909">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-909">Outlook</span></span>
- <span data-ttu-id="a7fcd-910">Исправлена проблема, из-за которой неверный шаблон мог отображаться среди выбранных</span><span class="sxs-lookup"><span data-stu-id="a7fcd-910">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-911">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-911">Access</span></span>
- <span data-ttu-id="a7fcd-912">Исправлена проблема, из-за которой могло быть затруднено чтение текста при использовании построителя масштаба для отображения длинного форматированного текста</span><span class="sxs-lookup"><span data-stu-id="a7fcd-912">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-913">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-913">Project</span></span>
- <span data-ttu-id="a7fcd-914">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-914">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="a7fcd-915">10 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-915">May 10, 2019</span></span>
<span data-ttu-id="a7fcd-916">Версия 1906 (сборка 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-916">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-917">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-917">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-918">Outlook</span></span>

<span data-ttu-id="a7fcd-919">**Размещение дополнительных сообщений на экране.** Выберите параметры "Вид" > "Уменьшить интервал", чтобы изменить интервалы между сообщениями.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-919">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-920">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-920">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-921">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-921">All</span></span>
- <span data-ttu-id="a7fcd-922">Исправлена проблема, из-за которой диалоговое окно "Сохранить как" могло отображать неправильный путь</span><span class="sxs-lookup"><span data-stu-id="a7fcd-922">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-923">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-923">Word</span></span> 
- <span data-ttu-id="a7fcd-924">Исправлена проблема, из-за которой не вставлялись некоторые выбранные элементы из области "Что вы хотите сделать?"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-924">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-925">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-925">Excel</span></span>
- <span data-ttu-id="a7fcd-926">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-926">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-927">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-927">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-928">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-928">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-929">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-929">Outlook</span></span>
- <span data-ttu-id="a7fcd-930">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-930">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-931">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-931">Access</span></span>
- <span data-ttu-id="a7fcd-932">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-932">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-933">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-933">Project</span></span>
- <span data-ttu-id="a7fcd-934">Исправлена проблема, из-за которой могло требоваться выделение для просмотра идентификатора задачи</span><span class="sxs-lookup"><span data-stu-id="a7fcd-934">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="a7fcd-935">3 мая 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-935">May 3, 2019</span></span>
<span data-ttu-id="a7fcd-936">Версия 1906 (сборка 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-936">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-937">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-937">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-938">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-938">Outlook</span></span>

<span data-ttu-id="a7fcd-939">**Все параметры шифрования в одном месте.** Просто откройте в параметрах раздел шифрования, чтобы выбрать способ защиты сообщений электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-939">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-940">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-940">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a7fcd-941">Все</span><span class="sxs-lookup"><span data-stu-id="a7fcd-941">All</span></span>
- <span data-ttu-id="a7fcd-942">Исправлена ошибка, из-за которой у некоторых пользователей возникали проблемы с синхронизацией OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="a7fcd-942">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-943">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-943">Word</span></span> 
- <span data-ttu-id="a7fcd-944">Исправлена ошибка, из-за которой в некоторых случаях запуск Word занимал много времени</span><span class="sxs-lookup"><span data-stu-id="a7fcd-944">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-945">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-945">Excel</span></span>
- <span data-ttu-id="a7fcd-946">Исправлена проблема, из-за которой внешние ссылки иногда удалялись из книг после обновления до более новой версии Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-946">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="a7fcd-947">Исправлена проблема, из-за которой у некоторых пользователей могли возникать сложности с выделением ячеек в новой книге</span><span class="sxs-lookup"><span data-stu-id="a7fcd-947">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-948">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-948">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-949">Исправлена проблема, из-за которой при преобразовании рисунков в текст неправильно согласовывались размеры шрифтов</span><span class="sxs-lookup"><span data-stu-id="a7fcd-949">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-950">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-950">Outlook</span></span>
- <span data-ttu-id="a7fcd-951">Исправлена проблема, из-за которой сохранение контакта из VCF-файла могло привести к получению пустых полей</span><span class="sxs-lookup"><span data-stu-id="a7fcd-951">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="a7fcd-952">Исправлена проблема, из-за которой сообщение могло оставаться в папке "Исходящие", хотя оно было отправлено</span><span class="sxs-lookup"><span data-stu-id="a7fcd-952">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="a7fcd-953">Исправлена проблема с аварийным завершением работы Outlook при просмотре сообщения DRM</span><span class="sxs-lookup"><span data-stu-id="a7fcd-953">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-954">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-954">Access</span></span>
- <span data-ttu-id="a7fcd-955">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-955">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-956">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-956">Project</span></span>
- <span data-ttu-id="a7fcd-957">Устранена ошибка, при которой редактор менялся с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="a7fcd-957">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="a7fcd-958">Устранена проблема, из-за которой неопубликованные задачи могли отображаться в опубликованной копии главного проекта</span><span class="sxs-lookup"><span data-stu-id="a7fcd-958">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="a7fcd-959">26 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-959">April 26, 2019</span></span>
<span data-ttu-id="a7fcd-960">Версия 1905 (сборка 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-960">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="a7fcd-961">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-961">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-962">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-962">Outlook</span></span>

<span data-ttu-id="a7fcd-963">**Общие календари стали обновляться быстрее.** Outlook может обновлять общие календари в Office 365 с помощью API REST.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-963">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="a7fcd-964">Включите предварительный просмотр для ускорения и повышения надежности обновлений в общих календарях.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-964">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-965">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-965">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="a7fcd-966">Улучшенные возможности совместного редактирования</span><span class="sxs-lookup"><span data-stu-id="a7fcd-966">Coauthoring improvements</span></span>

<span data-ttu-id="a7fcd-967">Улучшены возможности совместного редактирования с повышением вероятности получения измененного содержимого другими пользователями в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-967">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="a7fcd-968">Visio</span><span class="sxs-lookup"><span data-stu-id="a7fcd-968">Visio</span></span>

- <span data-ttu-id="a7fcd-969">**Экспорт визуальных элементов Visio из Power BI.** Визуальные элементы Visio для Power BI теперь правильно отображаются при экспорте отчетов Power BI в виде PDF-файлов, файлов PowerPoint и многих других.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-969">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-970">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-970">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-971">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-971">Word</span></span> 
- <span data-ttu-id="a7fcd-972">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-972">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-973">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-973">Excel</span></span>
- <span data-ttu-id="a7fcd-974">Устранена проблема, которая приводила к невозможности запуска макросов надстройки "Поиск решения"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-974">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="a7fcd-975">Устранена проблема, которая могла препятствовать импорту файлов Excel в SharePoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-975">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-976">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-976">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-977">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-977">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-978">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-978">Outlook</span></span>
- <span data-ttu-id="a7fcd-979">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-979">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-980">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-980">Access</span></span>
- <span data-ttu-id="a7fcd-981">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-981">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-982">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-982">Project</span></span>
- <span data-ttu-id="a7fcd-983">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-983">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="a7fcd-984">19 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-984">April 19, 2019</span></span>
<span data-ttu-id="a7fcd-985">Версия 1905 (сборка 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-985">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-986">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-986">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-987">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-987">Outlook</span></span>

<span data-ttu-id="a7fcd-988">**Получение предложений электронной почты при поиске пользователя.** Когда вы вводите имя пользователя в поле поиска, в предложения поиска включаются наиболее подходящие сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-988">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-989">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-989">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="a7fcd-990">Улучшенный интерфейс картограмм с использованием типов данных</span><span class="sxs-lookup"><span data-stu-id="a7fcd-990">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="a7fcd-991">Эта возможность является улучшением для пользователей, создающих картограммы с использованием географических типов данных Excel.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-991">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="a7fcd-992">Преимущество для пользователей заключается в более глубокой интеграции функций и повышенной точности в области, которую пользователь хочет отобразить на карте.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-992">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="a7fcd-993">Дополнительные преимущества включают возможность нанесения на карту многоугольников городов.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-993">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a7fcd-994">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-994">Getting Started:</span></span>

- <span data-ttu-id="a7fcd-995">Эта возможность является улучшением существующих функций в Excel.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-995">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="a7fcd-996">Чтобы использовать улучшение, преобразуйте расположения в объекты Rich и выполните построение с помощью картограмм.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-996">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-997">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-997">Scenarios to Try:</span></span>

- <span data-ttu-id="a7fcd-998">Пользователи могут попробовать указать на картах города, регионы, районы, страны и почтовые индексы.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-998">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-999">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-999">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a7fcd-1000">Все приложения</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1000">All Applications</span></span>
- <span data-ttu-id="a7fcd-1001">Исправлена ошибка, из-за которой диалоговое окно первого запуска отображалось при каждом запуске приложения</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1001">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="a7fcd-1002">Исправлена ошибка с возможным отсутствием ссылки SharePoint в диалоговом окне "Сохранить как".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1002">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="a7fcd-1003">Исправлена ошибка, из-за которой для пользователей неправильно отображалось диалоговое окно "Восстановить"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1003">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1004">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1004">Word</span></span> 
- <span data-ttu-id="a7fcd-1005">Исправлена ошибка, из-за которой у некоторых пользователей могла возникать ошибка с сообщением о недостатке памяти или места на диске при запросе шрифта</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1005">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="a7fcd-1006">Исправлена ошибка, из-за которой мог теряться фокус окна при переходе из области примечаний</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1006">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1007">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1007">Excel</span></span>
- <span data-ttu-id="a7fcd-1008">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1008">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1009">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1009">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1010">Исправлена ошибка, не позволявшая изменять размер фигур с фирменной символикой</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1010">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="a7fcd-1011">Исправлена ошибка, из-за которой приложение PowerPoint могло аварийно завершать работу при открытии файла в режиме защищенного просмотра</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1011">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1012">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1012">Outlook</span></span>
- <span data-ttu-id="a7fcd-1013">Исправлена ошибка, не позволявшая некоторым пользователям выделять китайские слова</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1013">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="a7fcd-1014">Исправлена ошибка с неправильным вычислением сроков действия</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1014">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1015">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1015">Access</span></span>
- <span data-ttu-id="a7fcd-1016">Исправлена ошибка, не позволявшая некоторым пользователям применять построитель макросов</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1016">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="a7fcd-1017">Исправлена ошибка, из-за которой при печати отчета печаталась только первая страница</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1017">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="a7fcd-1018">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при наведении указателя на гиперссылку</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1018">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="a7fcd-1019">Исправлена проблема, приводившая к отображению некоторых элементов вне экрана при использовании представления "Схема данных"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1019">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1020">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1020">Project</span></span>
- <span data-ttu-id="a7fcd-1021">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1021">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="a7fcd-1022">12 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1022">April 12, 2019</span></span>
<span data-ttu-id="a7fcd-1023">Версия 1905 (сборка 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1023">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-1024">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1024">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1025">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1025">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="a7fcd-1026">Получение интеллектуальных данных с помощью Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1026">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="a7fcd-1027">Импортируйте интеллектуальные данные или ссылайтесь на них и взгляните по-новому на свою классическую базу данных с помощью интеллектуальных технологий.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1027">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1028">Важные исправления</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1028">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a7fcd-1029">Все приложения</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1029">All Applications</span></span>
 - <span data-ttu-id="a7fcd-1030">Исправлена ошибка, не позволявшая некоторым пользователям сохранять файлы в облачных расположениях</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1030">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="a7fcd-1031">Исправлена ошибка, из-за которой могла открываться неправильная область из ленты</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1031">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1032">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1032">Word</span></span> 
- <span data-ttu-id="a7fcd-1033">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1033">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1034">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1034">Excel</span></span>
- <span data-ttu-id="a7fcd-1035">Исправлена ошибка, из-за которой для пользователей отображалось сообщение об ошибке, относящееся к связанным типам данных, если книга не содержала связанные типы данных</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1035">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="a7fcd-1036">Исправлена ошибка, из-за которой URL-ссылки в документе Word могли изменяться в зависимости от способа просмотра (локально или в Интернете)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1036">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1037">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1037">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1038">Исправлена ошибка, из-за которой мог происходить сбой приложения после отмены всех изменений на вкладке "Анимация"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1038">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1039">Outlook</span></span>
- <span data-ttu-id="a7fcd-1040">Исправлена ошибка, не позволявшая некоторым пользователям изменять поле "Заметки" для контактов в общедоступной папке</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1040">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="a7fcd-1041">Исправлена ошибка, из-за которой мог возникать конфликт между датами окончания срока действия и датами удаления</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1041">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1042">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1042">Access</span></span>
- <span data-ttu-id="a7fcd-1043">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1043">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1044">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1044">Project</span></span>
- <span data-ttu-id="a7fcd-1045">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1045">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="a7fcd-1046">5 апреля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1046">April 5, 2019</span></span>
<span data-ttu-id="a7fcd-1047">Версия 1904 (сборка 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1047">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-1048">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1048">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1049">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1049">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="a7fcd-1050">Outlook для Windows: настройка параметров сортировки почты и предоставление к ним общего доступа</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1050">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="a7fcd-1051">Ваши параметры сортировки почты хранятся в облаке, поэтому можно наслаждаться единообразным интерфейсом при использовании Outlook для Windows и Outlook в Интернете с любого устройства.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1051">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1052">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1052">Getting Started:</span></span>

<span data-ttu-id="a7fcd-1053">На вкладке "Общие" в разделе "Файл" > "Параметры" есть новый параметр "Хранить мои параметры Outlook в облаке".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1053">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="a7fcd-1054">Пользователям нужно установить флажок, чтобы разрешить перенос параметра сортировки почты в другие экземпляры классической версии Outlook и Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1054">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1055">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1055">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-1056">Измените сортировку почты на компьютере с включенными облачными параметрами.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1056">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="a7fcd-1057">Перейдите в Outlook Web App и убедитесь, что этот параметр также применен.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1057">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="a7fcd-1058">Измените настройки сортировки почты в Outlook Web App и запустите классическую версию Outlook, чтобы увидеть применение этих настроек.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1058">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1059">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1059">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="a7fcd-1060">В режиме "Средства обучения" реализована поддержка дополнительных цветов страниц</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1060">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="a7fcd-1061">Средства обучения в Word поддерживают дополнительные цветовые темы страницы, что позволяет менять цвет фона страницы.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1061">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="a7fcd-1062">Многие люди сталкиваются со сложностями при чтении на полностью белом или черном фоне, поэтому мы расширили выбор цветов в Word для компьютеров с Windows и Mac OS.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1062">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1063">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1063">Getting Started:</span></span>

<span data-ttu-id="a7fcd-1064">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1064">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1065">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1065">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-1066">Чтобы воспользоваться этой возможностью, перейдите на вкладку "Вид", нажмите кнопку "Средства обучения" и выберите элемент "Цвет страницы".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1066">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1067">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1067">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="a7fcd-1068">Расширение возможностей для творчества с помощью анимированных трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1068">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="a7fcd-1069">Теперь Office поддерживает анимированные модели, воспроизводимые в редакторе, чтобы вы могли оживить свои листы!</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1069">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1070">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1070">Getting Started:</span></span>

1. <span data-ttu-id="a7fcd-1071">Откройте Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1071">Open Excel</span></span>
2. <span data-ttu-id="a7fcd-1072">Вставьте анимированную трехмерную модель (вскоре будут доступны в сообществе Remix, а пока их можно найти здесь: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1072">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="a7fcd-1073">Анимированная модель будет воспроизводиться в редакторе!</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1073">The animated model will play in the editor!</span></span> <span data-ttu-id="a7fcd-1074">Проверьте режим слайд-шоу, она будет воспроизводиться и там!</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1074">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="a7fcd-1075">На ленте форматирования трехмерных моделей можно ознакомиться с дополнительными анимационными сценами в модели</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1075">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1076">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1076">Scenarios to Try:</span></span>

1. <span data-ttu-id="a7fcd-1077">Вставьте анимированную модель и посмотрите, как она будет воспроизводиться в редакторе</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1077">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="a7fcd-1078">Узнайте, какие анимационные сцены доступны для анимированной модели в коллекции "Сцены" на ленте форматирования трехмерных моделей</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1078">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="a7fcd-1079">Можно воспроизводить или приостанавливать анимацию с помощью ленты, мини-панели или клавиши ПРОБЕЛ.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1079">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1080">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1080">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a7fcd-1081">Все приложения</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1081">All Applications</span></span>
- <span data-ttu-id="a7fcd-1082">Мы исправили ошибку, когда значок приложения для Excel может отображаться неправильно в контекстном меню.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1082">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="a7fcd-1083">Мы исправили ошибку, когда после установки обновления может исчезать кнопка меню "Файл".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1083">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="a7fcd-1084">Исправлена проблема, в результате которой может измениться пользовательская лицензия.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1084">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1085">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1085">Word</span></span> 
- <span data-ttu-id="a7fcd-1086">Исправлена проблема с неправильным отображением текста при определенных уровнях масштабирования.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1086">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1087">Excel</span></span>
- <span data-ttu-id="a7fcd-1088">Мы исправили ошибку, в результате которой пользователи могли не видеть запрос на сохранение книги после внесения изменений.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1088">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="a7fcd-1089">Мы исправили ошибку, когда событие BeforeSave не запускалось, если пользователь предоставил общий доступ к книге.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1089">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="a7fcd-1090">Исправлена проблема, когда изменение размера столбца на менее чем 6 пикселей вызывает появление сообщения об ошибке.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1090">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="a7fcd-1091">Исправлена ошибка, когда Excel игнорирует метку Application.Visible.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1091">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="a7fcd-1092">Исправлена ошибка, когда стрелки трассировки остаются на неактивных закрепленных областях.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1092">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="a7fcd-1093">Исправлена ошибка, когда форматирование ячеек дат и валют может изменяться при открытии книги.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1093">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="a7fcd-1094">Мы исправили ошибку, когда подсказки могли неожиданно перемещаться</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1094">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="a7fcd-1095">Мы исправили ошибки локализации редактора Power Query</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1095">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="a7fcd-1096">Мы устранили проблему, когда рабочая книга могла удаляться из вложений при отправке по электронной почте.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1096">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1097">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1097">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1098">Мы устранили проблему с длительным временем, которое может требоваться на копирование форм.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1098">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1099">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1099">Outlook</span></span>
- <span data-ttu-id="a7fcd-1100">Мы устранили проблему с аварийным завершением работы Outlook при использовании инструмента рисования</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1100">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="a7fcd-1101">Устранена проблема локализации при составлении HTML-сообщений электронной почты</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1101">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="a7fcd-1102">Мы устранили проблему, когда пользователи сталкивались с трудностями при выборе нижней панели</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1102">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1103">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1103">Access</span></span>
- <span data-ttu-id="a7fcd-1104">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1104">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1105">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1105">Project</span></span>
- <span data-ttu-id="a7fcd-1106">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1106">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="a7fcd-1107">22 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1107">March 22, 2019</span></span>
<span data-ttu-id="a7fcd-1108">Версия 1904 (сборка 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1108">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="a7fcd-1109">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1109">New Features</span></span>

- <span data-ttu-id="a7fcd-1110">**Средства контроля конфиденциальности.** Новые, обновленные и улучшенные средства контроля для диагностических данных и сетевых функций.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1110">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="a7fcd-1111">Дополнительные сведения <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="a7fcd-1111">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="a7fcd-1112">**Новый дизайн значков Office.** Дизайн значков Office был изменен с целью отобразить простой, мощный и интеллектуальный интерфейс Office.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1112">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1113">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1113">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1114">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1114">Word</span></span> 
- <span data-ttu-id="a7fcd-1115">Устранена ошибка, при которой в интерфейсе пользователя постоянно отображается "Проверка изменений".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1115">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1116">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1116">Excel</span></span>
- <span data-ttu-id="a7fcd-1117">Устранена ошибка, при которой приложение аварийно завершало работу после перемещения листа</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1117">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="a7fcd-1118">Устранена ошибка, при которой приложение аварийно завершало работу после сохранения в формате PDF</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1118">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="a7fcd-1119">Устранена ошибка, при которой диалоговое окно сохранения не воспринимало некоторые корейские символы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1119">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1120">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1120">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1121">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1121">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1122">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1122">Outlook</span></span>
- <span data-ttu-id="a7fcd-1123">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1123">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1124">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1124">Access</span></span>
- <span data-ttu-id="a7fcd-1125">Исправлено сообщение об ошибке в Access, при которой создавался дополнительный ярлык для Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1125">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="a7fcd-1126">Устранена ошибка, при которой данные со связанного сайта SharePoint отображались неправильно</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1126">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1127">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1127">Project</span></span>
- <span data-ttu-id="a7fcd-1128">Устранена ошибка, при которой языковые параметры менялись с китайского на английский язык</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1128">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="a7fcd-1129">Устранена ошибка, при которой приложение аварийно завершало работу при синхронизации с SharePoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1129">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="a7fcd-1130">15 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1130">March 15, 2019</span></span>
<span data-ttu-id="a7fcd-1131">Версия 1904 (сборка 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1131">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-1132">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1132">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1133">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1133">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="a7fcd-1134">Режим фокусировки</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1134">Focus Mode</span></span>

<span data-ttu-id="a7fcd-1135">Хотите, чтобы вас ничего не отвлекало от работы? Переключитесь в режим фокусировки в меню "Вид".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1135">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="a7fcd-1136">Только для обладателей подписки на Office 365.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1136">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1137">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1137">Getting Started:</span></span>

<span data-ttu-id="a7fcd-1138">Кнопка "Фокус" вкладки "Вид" в строке состояния ленты с кнопкой "Фокус"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1138">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1139">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1139">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-1140">Переход в режим фокусировки и работа в интерфейсе фокусировки</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1140">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1141">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1141">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1142">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1142">Word</span></span> 
- <span data-ttu-id="a7fcd-1143">Исправлена проблема, из-за которой изображения в документе, сохраненном в формате PDF, имели неправильное значение точек на дюйм</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1143">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1144">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1144">Excel</span></span>
- <span data-ttu-id="a7fcd-1145">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1145">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1146">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1146">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1147">Исправлена проблема, из-за которой область примечаний открывалась и закрывалась неправильно</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1147">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="a7fcd-1148">Исправлена проблема, из-за которой приложение могло аварийно завершать работу при удалении видео</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1148">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="a7fcd-1149">Исправлена проблема, когда некоторые экземпляры приложения не запускались.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1149">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1150">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1150">Outlook</span></span>
- <span data-ttu-id="a7fcd-1151">Исправлена проблема с неправильными уведомлениями о прочтении при просмотре на японском языке.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1151">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1152">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1152">Access</span></span>
- <span data-ttu-id="a7fcd-1153">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1153">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1154">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1154">Project</span></span>
- <span data-ttu-id="a7fcd-1155">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1155">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="a7fcd-1156">8 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1156">March 8, 2019</span></span> 
<span data-ttu-id="a7fcd-1157">Версия 1903 (сборка 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1157">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-1158">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1158">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1159">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1159">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="a7fcd-1160">Находите нужные элементы с помощью Поиска (Майкрософт)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1160">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="a7fcd-1161">С помощью поиска Майкрософт можно найти все файлы, команды и пользователей, которые необходимы для выполнения работы.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1161">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1162">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1162">Getting Started:</span></span>

- <span data-ttu-id="a7fcd-1163">Эта функция выделяется вверху пользовательского интерфейса в заголовке.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1163">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1164">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1164">Scenarios to Try:</span></span>

- <span data-ttu-id="a7fcd-1165">Поиск учебного заведения, недавнего документа или часто используемых команд ленты</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1165">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="a7fcd-1166">Поиск статьи или темы и получение дополнительных сведений о ней</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1166">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="a7fcd-1167">Совместное редактирование</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1167">CoAuthoring</span></span>

<span data-ttu-id="a7fcd-1168">Вам надоело получать блокировку на документы с макросами?</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1168">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="a7fcd-1169">Теперь DOCM-файлы в OneDrive для бизнеса поддерживают одновременное редактирование несколькими авторами.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1169">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1170">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1170">Getting Started:</span></span>

<span data-ttu-id="a7fcd-1171">Пользователю не нужно нажимать какие-либо кнопки в пользовательском интерфейсе, чтобы применить эту возможность.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1171">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="a7fcd-1172">Она включена по умолчанию для DOCM-файлов в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1172">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="a7fcd-1173">Чтобы применить ее, пользователю нужно сохранить DOCM-файл в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1173">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1174">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1174">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-1175">Создайте DOCM-файл в OneDrive для бизнеса, поделитесь им с коллегами и работайте совместно!</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1175">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1176">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1176">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1177">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1177">Word</span></span> 
- <span data-ttu-id="a7fcd-1178">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1178">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="a7fcd-1179">Решена проблема со сбоем, происходившим при ответе на примечания</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1179">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="a7fcd-1180">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1180">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1181">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1181">Excel</span></span>
- <span data-ttu-id="a7fcd-1182">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1182">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1183">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1183">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1184">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1184">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1185">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1185">Outlook</span></span>
- <span data-ttu-id="a7fcd-1186">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1186">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a7fcd-1187">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1187">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a7fcd-1188">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1188">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1189">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1189">Access</span></span>
- <span data-ttu-id="a7fcd-1190">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1190">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a7fcd-1191">Исправлена проблема, из-за которой пользователи не могли присвоить свойству DisplayControl для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1191">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1192">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1192">Project</span></span>
- <span data-ttu-id="a7fcd-1193">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1193">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="a7fcd-1194">1 марта 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1194">March 1, 2019</span></span> 
<span data-ttu-id="a7fcd-1195">Версия 1903 (сборка 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1195">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-1196">Новые возможности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1196">What's New</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1197">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1197">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="a7fcd-1198">Синхронизированные цвета для отслеживания изменений, примечаний и совместной работы в режиме реального времени</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1198">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="a7fcd-1199">Исправления в наших продуктах теперь обеспечивают отображение одинаковым цветом примечаний, изменений и указателя мыши при совместной работе.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1199">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1200">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1200">Getting Started:</span></span>

<span data-ttu-id="a7fcd-1201">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1201">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="a7fcd-1202">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1202">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1203">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1203">Scenarios to Try:</span></span>

<span data-ttu-id="a7fcd-1204">Откройте документ SharePoint или OneDrive, открытый другими пользователями.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1204">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="a7fcd-1205">Убедитесь, что цвет исправлений и примечаний пользователя совпадает с цветом его указателя.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1205">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1206">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1206">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1207">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1207">Word</span></span> 
- <span data-ttu-id="a7fcd-1208">Решена проблема со сбоем, происходившим при нажатии клавиши ESC в параметрах</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1208">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="a7fcd-1209">Исправлена проблема с копированием и вставкой из Word в PowerPoint Online</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1209">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1210">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1210">Excel</span></span>
- <span data-ttu-id="a7fcd-1211">Исправлена проблема, из-за которой копирование ячейки в Excel приводило к высокой загрузке ЦП при открытом защищенном документе и документе с возможностью редактирования</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1211">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1212">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1212">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1213">Исправлена проблема с размером изображения слайда при использовании @упоминаний в PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1213">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1214">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1214">Outlook</span></span>
- <span data-ttu-id="a7fcd-1215">Исправлена проблема, из-за которой поиск Outlook не учитывал выбранную сортировку в хронологическом порядке</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1215">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a7fcd-1216">Исправлена проблема, из-за которой кнопка ленты "Открыть эту задачу" для рабочего процесса не срабатывала в некоторых сообщениях электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1216">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a7fcd-1217">Исправлена проблема, из-за которой Outlook не очищал помещения после выбора пользователем доступного помещения в средстве "Поиск комнаты"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1217">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1218">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1218">Access</span></span>
- <span data-ttu-id="a7fcd-1219">Обновлен текст запроса, отображаемый для подтверждения обновления связей таблицы с источником данных</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1219">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="a7fcd-1220">Исправлено диалоговое окно импорта и экспорта, в котором применялся белый текст на белом фоне в темной теме</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1220">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a7fcd-1221">Исправлена проблема, из-за которой пользователи не могли присвоить свойству "Тип элемента управления" для логического поля значение "Текстовое поле" в конструкторе таблиц</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1221">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1222">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1222">Project</span></span>
- <span data-ttu-id="a7fcd-1223">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1223">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="a7fcd-1224">15 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1224">February 15, 2019</span></span> 
<span data-ttu-id="a7fcd-1225">Версия 1903 (сборка 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1225">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a7fcd-1226">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1226">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1227">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1227">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="a7fcd-1228">Улучшения перехода "Трансформация" — трансформация по имени</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1228">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="a7fcd-1229">Укажите фигуры, которые нужно трансформировать</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1229">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1230">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1230">Getting Started:</span></span>

- <span data-ttu-id="a7fcd-1231">Чтобы при переходе "Трансформация" два объекта обрабатывались как одинаковые, пользователь может переименовать фигуры с помощью области выделения.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1231">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="a7fcd-1232">Имя должно начинаться с двух восклицательных знаков</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1232">The name must be prefaced with “!!”</span></span> <span data-ttu-id="a7fcd-1233">("!!"), чтобы использовать его при трансформации для переопределения стандартного сопоставления, например "!!Имя".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1233">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="a7fcd-1234">Пользователи могут продолжать переименовывать фигуры, используя любые имена, которые не начинаются с "!!",</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1234">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="a7fcd-1235">не беспокоясь о том, что это изменит работу перехода "Трансформация".</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1235">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1236">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1236">Scenarios to Try:</span></span>

- <span data-ttu-id="a7fcd-1237">Вставьте фигуру на слайд, например прямоугольник</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1237">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="a7fcd-1238">Создайте новый слайд</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1238">Create a new slide</span></span>
- <span data-ttu-id="a7fcd-1239">Вставьте другую фигуру на втором слайде, например треугольник</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1239">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="a7fcd-1240">Откройте область выделения и присвойте имя "!!фигура" прямоугольнику на слайде 1 и треугольнику на слайде 2.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1240">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="a7fcd-1241">Примените переход "Трансформация" ко второму слайду</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1241">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="a7fcd-1242">Улучшения перехода "Трансформация" — графические элементы SmartArt</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1242">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="a7fcd-1243">Трансформация графических элементов SmartArt с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1243">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1244">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1244">Getting Started:</span></span>

<span data-ttu-id="a7fcd-1245">Аналогичное использование перехода "Трансформация" при применении графических элементов SmartArt</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1245">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1246">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1246">Scenarios to Try:</span></span>

- <span data-ttu-id="a7fcd-1247">Вставьте графический элемент SmartArt на слайд</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1247">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="a7fcd-1248">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1248">Duplicate the Slide</span></span>
- <span data-ttu-id="a7fcd-1249">Поменяйте размер, измените или переместите графический элемент SmartArt на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1249">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="a7fcd-1250">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1250">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="a7fcd-1251">Улучшения перехода "Трансформация" — таблицы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1251">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="a7fcd-1252">Трансформация таблиц с более плавными переходами</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1252">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a7fcd-1253">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1253">Getting Started:</span></span>
<span data-ttu-id="a7fcd-1254">Аналогичное использование перехода "Трансформация" при применении таблиц</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1254">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1255">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1255">Scenarios to Try:</span></span>

- <span data-ttu-id="a7fcd-1256">Вставьте таблицу на слайд</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1256">Insert a Table in a slide</span></span>
- <span data-ttu-id="a7fcd-1257">Продублируйте слайд</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1257">Duplicate the slide</span></span>
- <span data-ttu-id="a7fcd-1258">Поменяйте размер, измените или переместите таблицу на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1258">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="a7fcd-1259">Примените переход "Трансформация" к дублированному слайду</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1259">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="a7fcd-1260">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher и Visio</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1260">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="a7fcd-1261">Легкое переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1261">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="a7fcd-1262">Новый диспетчер учетных записей отображает все рабочие и личные учетные записи в одном месте и позволяет управлять переключением между ними.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1262">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="a7fcd-1263">Этот обновленный интерфейс уточняет способ выполненного входа и обеспечивает возможность переключения между рабочими и личными учетными записями без выхода из системы или появления сложных диалоговых окон.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1263">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="a7fcd-1265">Возможные варианты:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1265">Scenarios to Try:</span></span>
- <span data-ttu-id="a7fcd-1266">Переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1266">Switch between accounts</span></span>
- <span data-ttu-id="a7fcd-1267">Добавление новой учетной записи [Примечание. Рекомендуется сначала открыть "Файл" | "Учетная запись" | "Подключенные службы" и удалить все личные службы, подключенные к рабочей учетной записи и наоборот]</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1267">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="a7fcd-1268">Выход из учетной записи</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1268">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1269">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1269">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1270">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1270">Word</span></span> 
- <span data-ttu-id="a7fcd-1271">Исправлена проблема с предварительным просмотром контекста для таблиц и изображений</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1271">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1272">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1272">Excel</span></span>
- <span data-ttu-id="a7fcd-1273">Исправлена ошибка, из-за которой при использовании темы "Черная" текст в поле поиска автофильтра был белого цвета</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1273">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="a7fcd-1274">Исправлена проблема с согласованным пользовательским интерфейсом для новой надстройки Office</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1274">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1275">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1275">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1276">Исправлена проблема с автоматическим расширением области отображения во время презентации на ноутбуках и планшетах.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1276">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1277">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1277">Outlook</span></span>
- <span data-ttu-id="a7fcd-1278">Исправлена проблема с отображением кнопки "Отправить в OneNote"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1278">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1279">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1279">Access</span></span>
- <span data-ttu-id="a7fcd-1280">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1280">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1281">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1281">Project</span></span>
- <span data-ttu-id="a7fcd-1282">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1282">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="a7fcd-1283">11 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1283">February 11, 2019</span></span>
<span data-ttu-id="a7fcd-1284">Версия 1903 (сборка 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1284">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1285">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1285">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1286">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1286">Word</span></span> 
- <span data-ttu-id="a7fcd-1287">Исправлена ошибка, из-за которой некоторые настроенные стили нельзя было применить в Word Online</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1287">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="a7fcd-1288">Исправлены проблемы предварительного просмотра контекста, связанные с форматированными объектами в Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1288">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="a7fcd-1289">Исправлена ошибка, из-за которой при вставке списков происходил сбой Word.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1289">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1290">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1290">Excel</span></span>
- <span data-ttu-id="a7fcd-1291">Исправлена ошибка, из-за которой добавляемые пробелы после числовых форматов не отображались при отсутствии обозначения денежной единицы</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1291">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="a7fcd-1292">Исправлена проблема с автоматическим определением акций</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1292">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1293">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1293">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1294">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1294">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1295">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1295">Outlook</span></span>
- <span data-ttu-id="a7fcd-1296">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1296">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1297">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1297">Access</span></span>
- <span data-ttu-id="a7fcd-1298">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1298">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1299">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1299">Project</span></span>
- <span data-ttu-id="a7fcd-1300">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1300">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="a7fcd-1301">1 февраля 2019 г.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1301">February 1, 2019</span></span> 
<span data-ttu-id="a7fcd-1302">Версия 1902 (сборка 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1302">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a7fcd-1303">Важные исправления:</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1303">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="a7fcd-1304">Word</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1304">Word</span></span> 
- <span data-ttu-id="a7fcd-1305">Устранена проблема с изменением размера ячеек во внедренной таблице Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1305">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="a7fcd-1306">Устранена проблема с копированием и вставкой фигур на полотне</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1306">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="a7fcd-1307">Excel</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1307">Excel</span></span>
- <span data-ttu-id="a7fcd-1308">Исправлена ошибка с открытием файлов из Excel Web App</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1308">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="a7fcd-1309">Исправлена ошибка, вызывавшая сбой при сохранении CSV-файла в формате XLSX из-за длины имени файла</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1309">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="a7fcd-1310">Исправлено контекстное меню для отображения параметров контекстного меню</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1310">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a7fcd-1311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1311">PowerPoint</span></span>
- <span data-ttu-id="a7fcd-1312">Устранена проблема, из-за которой пользователи не могли использовать сочетания клавиш CTRL+ALT+7 и CTRL+ALT+8 для ввода квадратных скобок</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1312">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="a7fcd-1313">Исправлена ошибка, из-за которой при вставке локального видео в файл PPT уменьшалось место на диске "C"</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1313">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="a7fcd-1314">Исправлена кнопка "Публикация в Microsoft Stream", не отображавшаяся у некоторых пользователей</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1314">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="a7fcd-1315">Outlook</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1315">Outlook</span></span>
- <span data-ttu-id="a7fcd-1316">Исправлена ошибка, из-за которой в представлении задач в календаре неправильно отображалась тема задачи.</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1316">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="a7fcd-1317">Access</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1317">Access</span></span>
- <span data-ttu-id="a7fcd-1318">Исправлена проблема с масштабированием диаграмм</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1318">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="a7fcd-1319">Project</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1319">Project</span></span>
- <span data-ttu-id="a7fcd-1320">Устранен ряд проблем производительности и стабильности</span><span class="sxs-lookup"><span data-stu-id="a7fcd-1320">Various performance and stability fixes</span></span>
