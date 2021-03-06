# Краткое описание книги "Совершенный код" от Стива Макконелла

-----
 
# Содержание:

### I.  Основы разработки ПО

  1. Добро пожаловать в мир конструирования ПО!

  2. Метафоры, позволяющие лучше понять разработку ПО.

  3. Семь раз отмерь, один раз отрежь: предварительные условия.

  4. Основные решения, которые приходится принимать при конструировании.
    
### II. Высококачественный код.

  5. Проектирование при конструировании.

  6. Классы.

  7. Высококачественные методы.

  8. Защитные программирование.

  9. Процесс программирования с псведокодом.
    
### III. Переменные.

  10. Общие принципы использования переменных.

  11. Сила имен переменных.

  12. Основные типы данных.

  13. Нестандартные типы данных.
    
### IV. Операторы

  14. Организация последовательного кода.

  15. Условные операторы.

  16. Циклы.

  17. Нестандартные управляющие структуры.

  18. Табличные методы.

  19. Общшие вопросы управления.
    
### V. Усовершенствование кода.

  20. Качество ПО.

  21. Совместное конструирование.

  22. Тестирование, выполняемое разработчиками.

  23. Отладка.

  24. Рефакторинг.

  25. Стратегии оптимизации кода.

  26. Методики оптимизации кода.
    
### VI. Системные вопросы.

  27. Как размер программы влияет на конструирование.

  28. Управление конструированием.

  29. Интеграция.

  30. Инструменты программирования.
    
### VII. Мастерство программирования.

  31. Форматирование и стиль.

  32. Самодокументирующийся код.

  33. Личность.

  34. Основы мастерства.

  35. Где искать дополнительную информацию.
  
  -----
  
 # Описание:
 
### I.  Основы разработки ПО

##  1. Добро пожаловать в мир конструирования ПО!

 + Конструирование — главный этап разработки ПО, без которого не обходится ни один проект.

 + Основные этапы конструирования: детальное проектирование, кодирование, отладка, интеграция и тестирование приложения разработчиками (блочное тестирование и интеграционное тестирование).

 + Конструирование часто называют «кодированием» и «программированием».

 + От качества конструирования во многом зависит качество ПО.

 + В конечном счете ваша компетентность в конструировании ПО определяет то, насколько хороший вы программист.  Совершенствованию ваших навыков и посвящена оставшаяся часть этой книги.

##  2. Метафоры, позволяющие лучше понять разработку ПО.

 + Метафоры являются по природе эвристическими, а не алгоритмическими, поэтому зачастую они немного небрежны.

 + Метафоры помогают понять процесс разработки ПО, сопоставляя его с другими, более знакомыми процессами.

 + Некоторые метафоры лучше, чем другие.

 + Сравнение конструирования ПО с возведением здания указывает на необходимость тщательной подготовки к проекту и проясняет различие между крупными и небольшими проектами.

 + Аналогия между методами разработки ПО и инструментами в интеллектуальном инструментарии программиста наводит на мысль, что в распоряжении программистов имеется множество разных инструментов и что ни один инструмент не является универсальным. Выбор правильного инструмента — одно из условий эффективного программирования.

 + Метафоры не исключают друг друга. Используйте комбинацию метафор, наиболее эффективную в вашем случае.


##  3. Семь раз отмерь, один раз отрежь: предварительные условия.

 + Главной целью подготовки к конструированию является снижение риска. Убедитесь, что проводимая вами подготовка снижает риск, а не повышает его.

 + Если вы хотите разрабатывать высококачественное ПО, внимание к качеству должно быть частью процесса разработки ПО с начала до конца. Внимание к качеству в начале процесса оказывает наибольшее влияние на итоговое качество приложения.

 + Одним из аспектов профессии программиста является объяснение руководителям и коллегам процесса разработки ПО, в том числе важности адекватной подготовки к программированию.

 + Предварительные условия конструирования в большой степени зависят от типа проекта, над которым вы работаете: многие проекты призывают к использованию высокоитеративного подхода, другие — более последовательного.

 + При отсутствии грамотного определения проблемы вы можете на этапе конструирования потратить силы на решение неверной проблемы.

 + Если не проведена адекватная выработка требований, вы можете упустить важные детали проблемы. Изменения требований после конструирования обходятся в 20–100 раз дороже, чем на предыдущих этапах, поэтому перед началом программирования обязательно убедитесь в правильности требований.

 + Если не проведено адекватное проектирование архитектуры, во время конструирования вы можете решать верную проблему неверным способом. По мере написания кода для неверной архитектуры цена изменений архитектуры возрастает, так что перед началом программирования вы должны проверить и правильность архитектуры.

 + Выбор подхода к конструированию должен определяться принятым подходом к предварительным условиям конструирования.

##  4. Основные решения, которые приходится принимать при конструировании.

 + Каждый язык программирования имеет достоинства и недостатки. Вы должны знать отдельные достоинства и недостатки используемого языка.

 + Определите конвенции программирования до начала программирования. Позднее адаптировать к ним код станет почти невозможно.

 + Методик конструирования слишком много, чтобы использовать все в одном проекте. Тщательно выбирайте методики, наиболее подходящие для вашего проекта.

 + Спросите себя, являются ли используемые вами методики программирования ответом на выбранный язык программирования или их выбор был определен языком. Помните, что программировать следует с использованием языка, а не на языке.

 + Эффективность конкретных подходов и даже возможность их применения зависит от стадии развития соответствующей технологии. Определите стадию развития используемой технологии и адаптируйте к ней свои планы и ожидания.

##  5. Проектирование при конструировании.

 + Главным Техническим Императивом Разработки ПО является управление сложностью. Управлять сложностью будет гораздо легче, если при проектировании вы будете стремиться к простоте.

 + Есть два общих способа достижения простоты: минимизация объема существенной сложности, с которой приходится иметь дело в любой конкретный момент времени, и подавление необязательного роста несущественной сложности.

 + Проектирование — эвристический процесс. Слепое следование какой#либо единственной методологии подавляет творческое мышление и снижает качество ваших программ.

 + Оптимальный процесс проектирования итеративен; чем больше вариантов проектирования вы попробуете, тем удачнее будет ваш окончательный проект.

 + Одной из самых полезных концепций проектирования является сокрытие информации. Вопрос «Что мне скрыть?» устраняет много сложных проблем проектирования.

 + Много полезной и интересной информации о проектировании можно найти в других книгах. Описанные в этой главе идеи — лишь вершина айсберга.

##  6. Классы.

 + Интерфейс класса должен формировать согласованную абстракцию. Многие проблемы объясняются нарушением одного этого принципа.

 + Интерфейс класса должен что#то скрывать — особенности взаимодействия с системой, аспекты проектирования или детали реализации.

 + Включение обычно предпочтительнее, чем наследование, если только вы не моделируете отношение «является».

 + Наследование — полезный инструмент, но оно повышает сложность, что противоречит Главному Техническому Императиву Разработки ПО, которым является управление сложностью.

 + Классы — главное средство управления сложностью. Уделите их проектированию столько времени, сколько нужно для достижения этой цели.

##  7. Высококачественные методы.


 + Самая важная, но далеко не единственная причина создания методов — улучшение интеллектуальной управляемости программы. Сокращение кода — не такая уж и важная причина; повышение его удобочитаемости, надежности и облегчение его изменения куда важнее.

 + Иногда огромную выгоду можно извлечь, создав отдельный метод для простой операции.

 + Связность методов можно разделить на несколько видов. Самая лучшая — функциональная — достижима практически всегда.

 + Имя метода является признаком его качества. Плохое, но точное имя часто указывает на плохое проектирование метода. Плохое и неточное имя не описывает роль метода. Как бы то ни было, плохое имя предполагает, что программу нужно изменить.

 + Функцию следует использовать, только когда главной целью метода является возврат конкретного значения, описываемого именем функции.

 + Добросовестные программисты используют методы#макросы с осторожностью и только в крайнем случае.

##  8. Защитные программирование.

 + Промышленный код должен обрабатывать ошибки более изощренно, чем по принципу «мусор на входе — мусор на выходе».

 + С помощью технологии защитного программирования ошибки легче находить, легче исправлять, и они наносят меньше вреда промышленному коду.

 + Утверждения позволяют обнаружить ошибки на ранней стадии, особенно в больших системах, системах повышенной надежности и в системах с часто изменяемым кодом.

 + Выбор способа обработки некорректных входных данных — это ключевое решение обработки ошибок, принимаемое на этапе высокоуровневого проектирования.

 + Исключения предоставляют возможность обработки ошибок в измерении, отличном от нормального хода алгоритма. Если они используются с осторожностью, то являются важным дополнением в интеллектуальном инструментальном наборе программиста. Применять их следует после сравнения с другими технологиями обработки ошибок.

 + Ограничения, применяемые к промышленной версии системы, не обязательно должны относиться и ко времени разработки. Пользуясь этим преимуществом, вы можете добавлять в отладочную версию любой код, помогающий быстро выявлять ошибки.

##  9. Процесс программирования с псведокодом.

 + Конструирование классов и методов — процесс итеративный. Особенности, замечаемые при конструировании отдельных методов, заставляют возвращаться к проектированию класса.

 + Написание хорошего псевдокода предполагает употребление понятного естественного языка без специфических особенностей конкретного языка программирования, а также формулировок на уровне намерений (описания сути конструкции, а не способов ее работы).

 + Процесс Программирования с Псевдокодом — полезный инструмент детального проектирования, упрощающий кодирование. Псевдокод транслируется непосредственно в комментарии, гарантируя их адекватность и полезность.

 + Не останавливайтесь на первой придуманной вами конструкции — испробуйте несколько подходов и выберите лучший, прежде чем писать код.

 + Проверяйте свою работу на каждом шаге и просите об этом других. При этом вы отловите ошибки на наименее дорогостоящем уровне, когда вы вложили в работу меньше усилий.

##  10. Общие принципы использования переменных.

 + Неграмотная инициализация данных часто приводит к ошибкам. Описанные в этой главе способы инициализации позволят избежать проблем, связанных с неожиданными первоначальными значениями переменных.

 + Минимизируйте область видимости каждой переменной. Группируйте обращения к переменным. Старайтесь делать переменные локальными для методов или классов. Избегайте глобальных данных.

 + Располагайте команды, использующие одни и те же переменные, как можно ближе друг к другу.

 + Раннее связывание ограничивает гибкость, но минимизирует сложность программы. Позднее связывание повышает гибкость, но за это приходится расплачиваться повышенной сложностью.

 + Используйте каждую переменную исключительно с одной целью.

##  11. Сила имен переменных.

 + Выбор хороших имен переменных — одно из главных условий понятности программы. С отдельными типами переменных — например, с индексами циклов и переменными статуса — связаны свои принципы именования.

 + Имена должны быть максимально конкретны. Имена, которые из#за невыразительности или обобщенности можно использовать более чем с одной целью, обычно являются плохими.

 + Конвенции именования позволяют провести различие между локальными данными, данными класса и глобальными данными, а также между именами типов, именованных констант, перечислений и переменных.

 + Над каким бы проектом вы ни работали, вам следует принять конвенцию именования переменных. При выборе типа конвенции следует учитывать размер программы и число работающих над ней программистов.

 + Современные языки программирования позволяют отказаться от сокращения имен. Если вы все#таки сокращаете имена, регистрируйте аббревиатуры в словаре проекта или используйте стандартизированные префиксы.

 + За чтением кода программисты проводят гораздо больше времени, чем за его написанием. Выбирайте имена так, чтобы они облегчали чтение кода, пусть даже за счет удобства его написания.

##  12. Основные типы данных.

 + Работа с определенными типами данных требует запоминания множества правил для каждого из них. Используйте список контрольных вопросов из этой главы, чтобы убедиться, что вы учли основные проблемы с ними.

 + Создание собственных типов, если ваш язык это позволяет, упрощает модификацию вашей программы и делает ее более самодокументируемой.

 + Прежде чем создавать простой тип с помощью typedef или его эквивалента, подумайте, не следует ли создать вместо него новый класс.

##  13. Нестандартные типы данных.

 + Структуры могут помочь сделать программы менее сложными, упростить их понимание и сопровождение.

 + Принимая решение использовать структуру, подумайте, не будет ли класс подходить лучше.

 + Работа с указателями чревата ошибками. Обезопасьте себя, используя методы или классы для доступа к ним и практику защитного программирования.

 + Избегайте глобальных переменных не только потому, что они опасны, но и потому что их можно заменить чем#то лучшим.

 + Если вы не можете отказаться от глобальных переменных, работайте с ними через методы доступа. Эти методы предоставляют все то же и даже больше, что и глобальные переменные.

##  14. Организация последовательного кода.

 + Главный принцип организации последовательного кода — упорядочение зависимостей.

 + Зависимости должны быть сделаны явными с помощью хороших имен методов, списков параметров, комментариев и — если последовательность кода достаточно критична — с помощью вспомогательных переменных.

 + Если порядковые зависимости в коде отсутствуют, старайтесь размещать взаимосвязанные выражения как можно ближе друг к другу.

##  15. Условные операторы.

 + В простых выражениях if%else обращайте внимание на порядок блоков if и else, особенно если они обрабатывают множество ошибок. Убедитесь, что номинальный вариант прослеживается ясно.

 + Для последовательностей if%then%else и операторов case выбирайте порядок, позволяющий улучшить читабельность.

 + Для перехвата ошибок используйте блок по умолчанию в операторе case или последний блок else в цепочке операторов if%then%else.

 + Управляющие конструкции не равнозначны. Выбирайте конструкцию, наиболее подходящую для данного участка кода.

##  16. Циклы.

 + Циклы сложны для понимания. Сохраняя их простыми, вы помогаете читателям вашего кода.

 + К способам упрощения циклов относятся: избегание экзотических видов циклов, минимизация вложенности, создание очевидных входов и выходов цикла и хранение служебного кода в одном месте.

 + Индексы цикла часто употребляются неправильно. Называйте их понятно и используйте только с одной целью.

 + Аккуратно продумайте весь цикл, чтобы убедиться, что он работает правильно во всех случаях и завершается при любых возможных обстоятельствах.

##  17. Нестандартные управляющие структуры.

 + Множественные возвраты могут улучшить читабельность и сопровождаемость метода и помогают избежать глубокой вложенности. Тем не менее использовать их нужно осторожно.

 + Рекурсия предлагает изящное решение для небольшого набора задач. Ее тоже нужно использовать аккуратно.

 + Иногда операторы goto — лучший способ облегчить чтение и сопровождение кода. Таких случаев очень немного. Используйте goto только как последнее средство.

##  18. Табличные методы.

 + Таблицы представляют собой альтернативу сложной логике и структурам с наследованием. Если вы понимаете, что сбиты с толку логикой программы или деревом наследования, спросите себя, не проще ли использовать таблицу поиска.

 + Основной вопрос при использовании таблиц состоит в выборе способа доступа к таблице. Вы можете использовать прямой, индексный или ступенчатый доступ.

 + Другой основной вопрос состоит в выборе того, что конкретно будет помещено в таблицу.

##  19. Общие вопросы управления.

 + Упрощение и облегчение чтения логических выражений вносит существенный вклад в качество вашего кода.

 + Глубокая вложенность затрудняет понимание метода. К счастью, вы сравнительно легко можете ее избежать.

 + Структурное программирование — это простая, но все еще злободневная идея: вы можете построить любую программу с помощью комбинации последовательностей, выборов и итераций.

 + Уменьшение сложности — ключ к написанию высококачественного кода.

##  20. Качество ПО.

 + Высокого качества можно достичь без дополнительных затрат, но для этого вы должны перераспределить ресурсы и предотвращать дефекты вместо того, чтобы их исправлять.

 + Стремление к одним характеристикам качества препятствует достижению других. Четко определите цели, имеющие для вас первостепенную важность, и сообщите об этом всем членам группы.

 + Никакая методика обнаружения дефектов не является достаточно эффективной. Тестирование само по себе — не самый лучший способ устранения ошибок. Составляя программу контроля качества, предусмотрите применение нескольких методик, позволяющих обнаружить разные виды ошибок.

 + Существуют многие эффективные методики контроля качества, применяемые как во время конструирования, так и до его начала. Чем раньше вы обнаружите дефект, тем слабее он переплетется с остальным кодом и тем меньше вреда он успеет принести.

 + В мире программирования контроль качества ориентирован на процесс. В отличие от промышленного производства разработка ПО не включает повторяющегося этапа, влияющего на конечный продукт, поэтому качество результата определяется процессом, используемым для разработки ПО.

##  21. Совместное конструирование.

 + Как правило, методики совместной разработки позволяют находить больше дефектов, чем тестирование, и делать это более эффективно.

 + Методики совместной разработки и тестирование приводят к обнаружению разных типов ошибок, поэтому программа контроля качества ПО должна включать и обзоры, и тестирование.

 + Главными аспектами формальной инспекции, обеспечивающими максимальную эффективность обнаружения дефектов, являются использование контрольных списков, подготовка, назначение хорошо определенных ролей и постоянное улучшение процесса. Формальная инспекция — более эффективный способ обнаружения дефектов, чем анализ проекта или кода.

 + Парное программирование и инспекции примерно эквивалентны по показателям расходов и качества итогового кода. Парное программирование может оказаться особенно полезным, если вы хотите сократить срок разработки системы. Некоторые разработчики предпочитают работать в паре, а не самостоятельно.

 + Формальные инспекции можно использовать для проверки не только кода, но и других результатов труда, таких как требования, проекты и тесты.

 + Анализ и чтение кода — альтернативы инспекциям. Чтение кода позволяет каждому участнику более эффективно использовать свое время.

##  22. Тестирование, выполняемое разработчиками.

 + Тестирование, выполняемое разработчиками, — один из важнейших элементов полной стратегии тестирования. Независимое тестирование не менее важно, но оно не является предметом этой книги.

 + Написание тестов до написания кода требует примерно того же времени и тех же усилий, что и создание тестов после кода, но сокращает циклы регистрации — отладки — исправления дефектов.

 + Даже если учесть, что тестирование имеет массу разновидностей, его все равно следует считать лишь одним из элементов хорошей программы контроля качества. Высококачественные методики разработки, позволяющие свести к минимуму число дефектов в требованиях и проектах, играют не менее, а то и более важную роль. Методики совместной разработки характеризуются не меньшей эффективностью обнаружения ошибок, чем тестирование, к тому же они позволяют находить другие ошибки.

 + Опираясь на базисное тестирование, анализ потоков данных, анализ граничных условий, классы плохих и классы хороших данных, вы можете создать много тестов детерминированным образом. Методика угадывания ошибок укажет вам на некоторые дополнительные тесты.

 + Обычно ошибки концентрируются в нескольких наиболее дефектных классах и методах. Найдите такой код, перепроектируйте его и перепишите.

 + Для тестовых данных обычно характерна более высокая плотность ошибок, чем для тестируемого кода. Так как поиск ошибок в тестовых данных требует времени, не приводя к какому бы то ни было улучшению кода, эти ошибки более досадны, чем ошибки программирования. Избегайте их, разрабатывая тесты столь же тщательно, что и код.

 + Автоматизация тестирования полезна вообще и практически необходима в случае регрессивного тестирования.

 + Чтобы процесс тестирования был максимально эффективным, сделайте его регулярным, выполняйте его оценку и используйте получаемую информацию для его улучшения.

##  23. Отладка.

 + Отладка — это тот этап разработки программы, от которого зависит возможность ее выпуска. Конечно, лучше всего вообще избегать ошибок, используя другие методики, описанные в этой книге. Однако потратить время на улучшение навыков отладки все же стоит, потому что эффективность отладки, выполняемой лучшими и худшими программистами, различается минимум в 10 раз.

 + Систематичный подход к поиску и исправлению ошибок — непременное условие успешности отладки. Организуйте отладку так, чтобы каждый тест приближал вас к цели. Используйте Научный Метод Отладки.

 + Прежде чем приступать к исправлению программы, поймите суть проблемы. Случайные предположения о причинах ошибок и случайные исправления только ухудшат программу.

 + Установите в настройках компилятора самый строгий уровень диагностики и устраняйте причины всех ошибок и предупреждений. Как вы исправите неуловимые ошибки, если будете игнорировать явные?

 + Инструменты отладки значительно облегчают разработку ПО. Найдите их и используйте, но не забывайте, что у вас есть еще и голова.

##  24. Рефакторинг.

 + Изменения программы неизбежны как во время первоначальной разработки, так и после выпуска первой версии.

 + Изменения могут приводить как к улучшению, так и к ухудшению ПО. Главное Правило Эволюции ПО заключается в том, что при эволюции кода внутреннее качество программы должно повышаться.

 + Одним из условий успешности рефакторинга является пристальное внимание к многочисленным предупреждающим знакам — «запахам», указывающим на необходимость рефакторинга.

 + Другое условие — изучение многих конкретных видов рефакторинга.

 + Заключительным условием успешности рефакторинга является следование стратегии безопасного рефакторинга. Одни подходы к рефакторингу лучше, а другие хуже.

 + Рефакторинг во время разработки — самая благоприятная возможность улучшения программы и внесения в нее всех изменений, которые вам так или иначе захочется внести позднее. Используйте эту возможность!

##  25. Стратегии оптимизации кода.

 + Производительность — всего лишь один из аспектов общего качества ПО, и, как правило, не самый важный. Оптимизация кода — лишь один из способов повышения производительности ПО, и тоже обычно не самый важный. Быстродействие программы и ее объем обычно в большей степени зависят не от эффективности кода, а от архитектуры программы, детального проектирования выбора структур данных и алгоритмов.

 + Важнейшее условие максимизации быстродействия кода — его количественная оценка. Она необходима для обнаружения областей, производительность которых действительно нуждается в повышении, а также для проверки того, что в результате оптимизации производительность повысилась, а не понизилась.

 + Как правило, основная часть времени выполнения программы приходится на небольшую часть кода. Не выполнив оценку, вы не найдете этот код.

 + Достижение желаемого повышения производительности кода при помощи его оптимизации обычно требует нескольких итераций.

 + Во время первоначального кодирования нет лучше способа подготовки к повышению производительности программы, чем написание ясного и понятного кода, поддающегося легкому изменению.

##  26. Методики оптимизации кода.

 + Результаты конкретных видов оптимизации во многом зависят от языка, компилятора и среды. Не оценив результатов оптимизации, вы не сможете сказать, помогает она программе или вредит.

 + Первый вид оптимизации часто далеко не самый лучший. Обнаружив эффективный вид оптимизации, продолжайте пробовать и, возможно, найдете еще более эффективный.

 + Оптимизация кода похожа на ядерную энергию — это противоречивая и эмоциональная тема. Кто#то считает, что оптимизация настолько ухудшает надежность и удобство сопровождения программы, что ее вообще выполнять не следует. Другие думают, что при соблюдении должной предосторожности она приносит пользу. Если вы решите использовать методики, описанные в этой главе, будьте внимательны и осторожны.

##  27. Как размер программы влияет на конструирование.

 + С ростом размера проекта появляется необходимость поддерживать взаимодействие. Смысл большинства подходов к методологии состоит в уменьшении проблем взаимодействия, поэтому методология должна жить или умереть в зависимости от ее вклада в облегчение взаимодействия.

 + При прочих равных, производительность в больших проектах будет ниже, чем в маленьких.

 + При прочих равных большие проекты будут содержать больше ошибок на 1000 строк кода, чем маленькие.

 + Деятельность, которая в малых проектах сама собой разумеется, в больших проектах должна быть тщательно спланирована. С ростом размера проекта конструирование занимает все меньшую ее часть.

 + Увеличение масштаба легковесной методологии обычно работает лучше, чем уменьшение масштаба тяжеловесной. Наиболее эффективный подход состоит в использовании «правильновесной» методологии.

##  28. Управление конструированием.

 + Хорошая практика кодирования может быть достигнута путем внедрения стандартов или более ловкими способами.

 + Управление конфигурацией при правильном применении делает работу программистов проще. Это особенно касается контроля изменений.

 + Правильная оценка ПО — сложная задача. Ключ к успеху — использование нескольких подходов, уточнение оценок по мере продвижения проекта и применение накопленных данных при выполнении оценки.

 + Измерения — это ключ к успешному управлению конструированием. Вы всегда сможете найти способы измерить любой аспект проекта, что будет лучше, чем полное отсутствие измерений. Точное измерение — ключ к точному составлению плана, контролю качества и улучшению процесса разработки.

 + Программисты и менеджеры — в первую очередь люди, и они лучше всего работают тогда, когда к ним относятся по#человечески.

##  29. Интеграция.

 + Последовательность конструирования и интеграционный подход влияют на порядок, в котором классы проектируются, кодируются и тестируются.

 + Порядок интеграции снижает затраты на тестирование и упрощает отладку.

 + Инкрементная интеграция имеет несколько вариантов, и, помимо совсем тривиальных проектов, любой из них лучше, чем поэтапная интеграция.

 + Лучший интеграционный подход для каждого конкретного проекта — обычно сочетание нисходящего, восходящего, риск#ориентированного и других интеграционных подходов. Т#образная интеграция и интеграция с вертикальным секционированием часто дают хорошие результаты.

 + Ежедневные сборки могут уменьшить проблемы с интеграцией, улучшить моральный климат среди разработчиков и предоставить полезную информацию, касающуюся управления проектом.

##  30. Инструменты программирования.

 + Хороший инструментарий может значительно облегчить вам жизнь.

 + Можно легко приобрести инструменты для редактирования, анализа качества кода, рефакторинга, управления версиями, отладки, тестирования и настройки кода.

 + Вы можете создать множество инструментов специального назначения.

 + Хорошие инструменты могут упростить наиболее утомительные аспекты разработки ПО, но они не могут исключить необходимость программирования, хотя и способствуют эволюции того понятия, которое мы вкладываем в слово «программирование».

##  31. Форматирование и стиль.

 + Главная цель визуального форматирования — это подчеркивание логической структуры кода. В критерии оценки достижения этой цели входят аккуратность, единообразие, удобство чтения и сопровождения кода.

 + Критерий хорошего внешнего вида имеет вторичное, далеко не основное значение. Однако если другие критерии соблюдены, а лежащий в основе код написан хорошо, то форматирование будет выглядеть привлекательно.

 + Visual Basic поддерживает явные блоки, а стандартное соглашение в Java предписывает их использование, поэтому, программируя на этих языках, вы можете применять явные блоки. В C++ хорошо смотрится эмуляция явных блоков или обозначение границ блоков с помощью пар begin%end.

 + Структурирование кода само по себе имеет большое значение. Конкретные соглашения менее важны, чем сам факт, что вы последовательно применяете определенные соглашения. Договоренности по форматированию, соблюдаемые лишь от случая к случаю, могут сильно ухудшить читаемость кода.

 + Многие аспекты форматирования сродни религиозным вопросам. Пытайтесь разделять объективные и субъективные предпочтения. Используйте явные критерии для обоснования вашей точки зрения при обсуждении стилевых предпочтений.

##  32. Самодокументирующийся код.

 + Вопрос о том, стоит ли комментировать код, вполне обоснован. При плохом выполнении комментирование является пустой тратой времени и иногда причиняет вред. При грамотном применении комментирование полезно.

 + Основная часть критически важной информации о программе должна содержаться в исходном коде. На протяжении жизни программы актуальности исходного кода уделяется больше внимания, чем актуальности любого другого ресурса, поэтому важную информацию полезно интегрировать в код.

 + Хороший код сам является самой лучшей документацией. Если код настолько плох, что требует объемных комментариев, попытайтесь сначала улучшить его.

 + Комментарии должны сообщать о коде что#то такое, что он не может сообщить сам — на уровне резюме или уровне цели.

 + Некоторые стили комментирования заставляют выполнять много нудной канцелярской работы. Используйте стиль, который было бы легко поддерживать.

##  33. Личность.

 + Способность к написанию программ напрямую зависит от личного характера.

 + Важнейшие качества программиста — скромность, любопытство, профессиональная честность, творчество и дисциплина, а также «просвещенная» лень.

 + Чтобы стать отличным программистом, можно не обладать особым талантом, но необходимо постоянно стремиться к самосовершенствованию.

 + Удивительно, но интеллект, опыт и настойчивость вредят программистам не меньше, чем помогают.

 + Многие программисты не ведут активного поиска новых сведений и методик, а полагаются на случайные столкновения с новой информацией на работе. Если вы посвятите небольшую долю своего времени чтению книг и изучению программирования, через несколько месяцев вы будете намного превосходить почти всех своих коллег.

 + Хороший характер во многом — продукт правильных привычек. Если хотите стать великолепным программистом, выработайте правильные привычки, а все остальное придет само собой.


##  34. Основы мастерства.

 + Главная цель программирования — управление сложностью.

 + Процесс программирования оказывает большое влияние на итоговый продукт.

 + Групповое программирование является в большей степени общением с другими людьми, а не с компьютером. Индивидуальное программирование — это в первую очередь общение с самим собой, а не с компьютером.

 + При неадекватном использовании конвенция программирования может оказаться лекарством, причиняющим больше вреда, чем болезнь; при грамотном — конвенция добавляет ценную структуру в среду разработки, помогает управлять сложностью и облегчает общение.

 + Программирование в терминах проблемы, а не решения помогает управлять сложностью.

 + Внимание к интеллектуальным предупреждающим знакам вроде сомнения особенно важно в программировании, потому что программирование — почти исключительно умственная деятельность.

 + Чем больше внимания итерации вы уделяете на конкретном этапе разработки, тем лучше будет результат этого этапа.

 + Догматичные методологии и разработка высококачественного ПО исключают друг друга. Заполняйте свой интеллектуальный инструментарий альтернативными подходами к программированию и улучшайте навык выбора инструмента, лучше всего подходящего для работы.
 
  
  
 
