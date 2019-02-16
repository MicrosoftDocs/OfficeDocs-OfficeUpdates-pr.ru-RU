---
<span data-ttu-id="3e057-101">Title: "заметки о выПуске для участников Office" MS. author: андревмо author: микхо Manager: андревмо MS. Date: 2/15/2019 МС. аудитория: Win32 Fast MS. Topic: Reference MS. Service: O365-ProPlus-локализатион_приорити: Critical MS. Collection: Релнотес_проплус Description: "в этой статье представлены краткие сведения о новых основных возможностях, исправлениях и известных проблемах.</span><span class="sxs-lookup"><span data-stu-id="3e057-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 2/15/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="3e057-102">Заметки о выПуске для участников программы предварительной оценки Office</span><span class="sxs-lookup"><span data-stu-id="3e057-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="3e057-p101">В этой статье содержатся заметки о выпуске для участников программы предварительной оценки для настольных систем Word, Excel, PowerPoint, Outlook, Access и Project для Windows. Каждую неделю мы выделим интересные новые функции, важные исправления и все важные проблемы, о которых нужно знать. Обратите внимание на то, что мы часто выгрузим компоненты (а иногда и даже исправления) для участников в течение определенного периода времени. Это позволяет нам обеспечить бесперебойную работу перед отправкой функции в более широкую аудиторию. Таким образом, если вы не видите ничего, описанного ниже, не беспокойтесь, что в конечном итоге вы получите его.</span><span class="sxs-lookup"><span data-stu-id="3e057-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-12-2019-version-1902-build-1133020014"></a><span data-ttu-id="3e057-108">12 2019 февраля версии 1902 (сборка 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="3e057-108">February 12 2019 Version 1902 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="3e057-109">Новые возможности:</span><span class="sxs-lookup"><span data-stu-id="3e057-109">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3e057-110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3e057-110">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="3e057-111">Расширения преобразования "трансформация" — трансформация по имени</span><span class="sxs-lookup"><span data-stu-id="3e057-111">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="3e057-112">Указание фигур для трансформации</span><span class="sxs-lookup"><span data-stu-id="3e057-112">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="3e057-113">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="3e057-113">Getting Started:</span></span>

- <span data-ttu-id="3e057-114">Чтобы получить трансФормацию для обработки двух объектов в виде одного объекта, пользователь может переименовать эти фигуры с помощью области выделения.</span><span class="sxs-lookup"><span data-stu-id="3e057-114">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="3e057-p102">Имя должно иметь приставку "!!" (два восклицательных знака), чтобы использовать его для переопределения поведения согласования по умолчанию, например "!! Расширением</span><span class="sxs-lookup"><span data-stu-id="3e057-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="3e057-p103">Пользователи могут продолжать переименовывать фигуры с любым именем, которое не начинается с "!!", не заботясь о том, что он изменит вид трансформации</span><span class="sxs-lookup"><span data-stu-id="3e057-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="3e057-119">Сценарии для попытки:</span><span class="sxs-lookup"><span data-stu-id="3e057-119">Scenarios to Try:</span></span>

- <span data-ttu-id="3e057-120">Вставка фигуры в слайд, пусть, например, прямоугольника</span><span class="sxs-lookup"><span data-stu-id="3e057-120">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="3e057-121">Создание нового слайда</span><span class="sxs-lookup"><span data-stu-id="3e057-121">Create a new slide</span></span>
- <span data-ttu-id="3e057-122">Вставка другой фигуры в 2-й слайд, пусть — треугольник</span><span class="sxs-lookup"><span data-stu-id="3e057-122">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="3e057-123">Откройте Селектионпане, переименуйте прямоугольник в слайде 1 на "!! фигуру и переименуйте треугольник в слайде 2 на "!! всплывающ</span><span class="sxs-lookup"><span data-stu-id="3e057-123">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="3e057-124">Применение трансформации на 2-м слайде</span><span class="sxs-lookup"><span data-stu-id="3e057-124">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="3e057-125">Улучшенные переходы по элементу SmartArt</span><span class="sxs-lookup"><span data-stu-id="3e057-125">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="3e057-126">Элемент SmartArt с более гладкими переходами</span><span class="sxs-lookup"><span data-stu-id="3e057-126">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="3e057-127">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="3e057-127">Getting Started:</span></span>

<span data-ttu-id="3e057-128">Использование элемента "трансформация" точно так же, как и для SmartArt</span><span class="sxs-lookup"><span data-stu-id="3e057-128">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="3e057-129">Сценарии для попытки:</span><span class="sxs-lookup"><span data-stu-id="3e057-129">Scenarios to Try:</span></span>

- <span data-ttu-id="3e057-130">Вставка элемента SmartArt в слайд</span><span class="sxs-lookup"><span data-stu-id="3e057-130">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="3e057-131">Дублирование слайда</span><span class="sxs-lookup"><span data-stu-id="3e057-131">Duplicate the Slide</span></span>
- <span data-ttu-id="3e057-132">Изменение или изменение размера и перемещение элемента SmartArt на дубликате слайда</span><span class="sxs-lookup"><span data-stu-id="3e057-132">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="3e057-133">Применение трансформации на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="3e057-133">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="3e057-134">Расширения преобразования «трансформация» — таблицы</span><span class="sxs-lookup"><span data-stu-id="3e057-134">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="3e057-135">Таблицы с более гладкими переходами</span><span class="sxs-lookup"><span data-stu-id="3e057-135">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="3e057-136">Начало работы:</span><span class="sxs-lookup"><span data-stu-id="3e057-136">Getting Started:</span></span>
<span data-ttu-id="3e057-137">Используйте элемент "трансформация" точно так же, как и с таблицами</span><span class="sxs-lookup"><span data-stu-id="3e057-137">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="3e057-138">Сценарии для попытки:</span><span class="sxs-lookup"><span data-stu-id="3e057-138">Scenarios to Try:</span></span>

- <span data-ttu-id="3e057-139">Вставка таблицы в слайд</span><span class="sxs-lookup"><span data-stu-id="3e057-139">Insert a Table in a slide</span></span>
- <span data-ttu-id="3e057-140">Дублирование слайда</span><span class="sxs-lookup"><span data-stu-id="3e057-140">Duplicate the slide</span></span>
- <span data-ttu-id="3e057-141">Изменение или изменение размера и перемещение таблицы на дубликате слайда</span><span class="sxs-lookup"><span data-stu-id="3e057-141">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="3e057-142">Применение трансформации на дублированном слайде</span><span class="sxs-lookup"><span data-stu-id="3e057-142">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="3e057-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher _Амп_ Visio</span><span class="sxs-lookup"><span data-stu-id="3e057-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="3e057-144">Простота переключения между учетными записями</span><span class="sxs-lookup"><span data-stu-id="3e057-144">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="3e057-p104">Новый диспетчер учетных записей показывает все ваши рабочие и личные учетные записи в одном месте, а также управляет переключением между ними. Этот обновленный интерфейс позволяет понять, как вы выполнили вход, и теперь вы можете переключаться между рабочими и личными учетными записями, не выполняя выход из сложных диалоговых окон или исходить их.</span><span class="sxs-lookup"><span data-stu-id="3e057-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>



#### <a name="scenarios-to-try"></a><span data-ttu-id="3e057-147">Сценарии для попытки:</span><span class="sxs-lookup"><span data-stu-id="3e057-147">Scenarios to Try:</span></span>
- <span data-ttu-id="3e057-148">Переключение между учетными записями</span><span class="sxs-lookup"><span data-stu-id="3e057-148">Switch between accounts</span></span>
- <span data-ttu-id="3e057-149">Добавление новой учетной записи [Note: сначала перейдите в раздел File | Учетная запись | Подключенные службы и удаляются все персональные службы, подключенные к рабочим учетным записям, и наоборот).</span><span class="sxs-lookup"><span data-stu-id="3e057-149">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="3e057-150">Выход из учетной записи</span><span class="sxs-lookup"><span data-stu-id="3e057-150">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="3e057-151">Существенные исправления:</span><span class="sxs-lookup"><span data-stu-id="3e057-151">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="3e057-152">Word</span><span class="sxs-lookup"><span data-stu-id="3e057-152">Word</span></span> 
- <span data-ttu-id="3e057-153">Исправлена ошибка, связанная с предварительным просмотром в контексте таблиц _Амп_ Images</span><span class="sxs-lookup"><span data-stu-id="3e057-153">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="3e057-154">Excel</span><span class="sxs-lookup"><span data-stu-id="3e057-154">Excel</span></span>
- <span data-ttu-id="3e057-155">Исправлена ошибка, из-за которой текст в поле поиска с автофильтром белый в черной теме</span><span class="sxs-lookup"><span data-stu-id="3e057-155">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="3e057-156">Мы зафиксированы вопросы ПОЛЬЗОВАТЕЛЬСКОГО интерфейса согласия с новой надстройкой Office</span><span class="sxs-lookup"><span data-stu-id="3e057-156">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3e057-157">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3e057-157">PowerPoint</span></span>
- <span data-ttu-id="3e057-158">Исправлена ошибка, связанная с автоматическим расширением экрана при показе слайдов на ноутбуках или планшетах.</span><span class="sxs-lookup"><span data-stu-id="3e057-158">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="3e057-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="3e057-159">Outlook</span></span>
- <span data-ttu-id="3e057-160">Исправлена ошибка, связанная с отображением на кнопке "отправить в OneNote"</span><span class="sxs-lookup"><span data-stu-id="3e057-160">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="3e057-161">Доступ</span><span class="sxs-lookup"><span data-stu-id="3e057-161">Access</span></span>
- <span data-ttu-id="3e057-162">Различные проблемы с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="3e057-162">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="3e057-163">Project</span><span class="sxs-lookup"><span data-stu-id="3e057-163">Project</span></span>
- <span data-ttu-id="3e057-164">Различные проблемы с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="3e057-164">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1902-build-1133020014"></a><span data-ttu-id="3e057-165">9 2019 февраля версии 1902 (сборка 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="3e057-165">February 9 2019 Version 1902 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="3e057-166">Существенные исправления:</span><span class="sxs-lookup"><span data-stu-id="3e057-166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="3e057-167">Word</span><span class="sxs-lookup"><span data-stu-id="3e057-167">Word</span></span> 
- <span data-ttu-id="3e057-168">Исправлена ошибка, из-за которой не удалось применить некоторые специальные стили к Word Online</span><span class="sxs-lookup"><span data-stu-id="3e057-168">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="3e057-169">Исправлены проблемы с предварительным предварительным просмотром контекста в Word</span><span class="sxs-lookup"><span data-stu-id="3e057-169">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="3e057-170">Исправлена ошибка, в результате которой при вставке списков произойдет сбой Word</span><span class="sxs-lookup"><span data-stu-id="3e057-170">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="3e057-171">Excel</span><span class="sxs-lookup"><span data-stu-id="3e057-171">Excel</span></span>
- <span data-ttu-id="3e057-172">Исправлена ошибка, из-за которой добавленные пробелы после числовых форматов больше не отображаются при отсутствии символа валюты</span><span class="sxs-lookup"><span data-stu-id="3e057-172">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="3e057-173">Исправлена ошибка, связанная с автоматическим обнаружением для акций</span><span class="sxs-lookup"><span data-stu-id="3e057-173">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3e057-174">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3e057-174">PowerPoint</span></span>
- <span data-ttu-id="3e057-175">Различные проблемы с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="3e057-175">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="3e057-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="3e057-176">Outlook</span></span>
- <span data-ttu-id="3e057-177">Различные проблемы с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="3e057-177">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="3e057-178">Доступ</span><span class="sxs-lookup"><span data-stu-id="3e057-178">Access</span></span>
- <span data-ttu-id="3e057-179">Различные проблемы с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="3e057-179">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="3e057-180">Project</span><span class="sxs-lookup"><span data-stu-id="3e057-180">Project</span></span>
- <span data-ttu-id="3e057-181">Различные проблемы с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="3e057-181">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="3e057-182">30 января 2019 г. версия 1902 (сборка 11326,20000)</span><span class="sxs-lookup"><span data-stu-id="3e057-182">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="3e057-183">Существенные исправления</span><span class="sxs-lookup"><span data-stu-id="3e057-183">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="3e057-184">Word</span><span class="sxs-lookup"><span data-stu-id="3e057-184">Word</span></span> 
- <span data-ttu-id="3e057-185">Исправлена ошибка, связанная с изменением размера ячеек во внедренной таблице Excel</span><span class="sxs-lookup"><span data-stu-id="3e057-185">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="3e057-186">Исправлена ошибка при копировании и вставке фигур на полотне</span><span class="sxs-lookup"><span data-stu-id="3e057-186">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="3e057-187">Excel</span><span class="sxs-lookup"><span data-stu-id="3e057-187">Excel</span></span>
- <span data-ttu-id="3e057-188">Исправлена ошибка при открытии файлов из Excel Web App</span><span class="sxs-lookup"><span data-stu-id="3e057-188">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="3e057-189">Исправлена ошибка, из-за которой сохраняется CSV-файл. XLSX завершился с ошибками из-за размера имени файла</span><span class="sxs-lookup"><span data-stu-id="3e057-189">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="3e057-190">Мы зафиксированы контекстное меню, чтобы отобразить параметры контекстного меню.</span><span class="sxs-lookup"><span data-stu-id="3e057-190">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3e057-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3e057-191">PowerPoint</span></span>
- <span data-ttu-id="3e057-192">Исправлена ошибка, из-за которой пользователи не могли использовать сочетание клавиш Ctrl + Alt + 7/Ctrl + Alt + 8, чтобы вводить квадратные скобки.</span><span class="sxs-lookup"><span data-stu-id="3e057-192">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="3e057-193">Исправлена ошибка, из-за которой при вставке локального видео в PPT будет уменьшено дисковое пространство "C".</span><span class="sxs-lookup"><span data-stu-id="3e057-193">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="3e057-194">Мы зафиксирована кнопка опубликовать в Microsoft Stream, которая не отображается для некоторых пользователей</span><span class="sxs-lookup"><span data-stu-id="3e057-194">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="3e057-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="3e057-195">Outlook</span></span>
- <span data-ttu-id="3e057-196">Исправлена ошибка, из — неправильное отображение темы задачи в представлении "Календарь"</span><span class="sxs-lookup"><span data-stu-id="3e057-196">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="3e057-197">Доступ</span><span class="sxs-lookup"><span data-stu-id="3e057-197">Access</span></span>
- <span data-ttu-id="3e057-198">Исправлена ошибка масштабирования диаграмм</span><span class="sxs-lookup"><span data-stu-id="3e057-198">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="3e057-199">Project</span><span class="sxs-lookup"><span data-stu-id="3e057-199">Project</span></span>
- <span data-ttu-id="3e057-200">Различные проблемы с производительностью и стабильностью</span><span class="sxs-lookup"><span data-stu-id="3e057-200">Various performance and stability fixes</span></span>
