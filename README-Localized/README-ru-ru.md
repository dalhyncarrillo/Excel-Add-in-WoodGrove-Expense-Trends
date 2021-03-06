# Excel-Add-in-JS-WoodGrove-Expense-Trends

Этот пример надстройки, позволяющей анализировать направления расходных операций через WoodGrove Bank, показывает создание привлекательной надстройки Excel с помощью API JavaScript для Microsoft Excel 2016. С помощью этой надстройки вы можете импортировать данные о расходных операциях в книгу, создать панель мониторинга и средства отслеживания, просматривать и анализировать направления, а также отслеживать специальные операции, например благотворительные пожертвования и последующие действия. В этом примере представлено два варианта. Один предназначен для области задач, а другой предполагает использование команд надстроек. На приведенных ниже рисунках показаны основные экраны этой надстройки.

![Надстройка, позволяющая анализировать направления расходных операций через WoodGrove Bank (лента)] (../images/woodgrove_taskpane_ribbon.PNG)

![Надстройка, позволяющая анализировать направления расходных операций через WoodGrove Bank (исходная область задач)] (../images/woodgrove_taskpane_import.PNG)

![Надстройка, позволяющая анализировать направления расходных операций через WoodGrove Bank (лист с данными об операциях)] (../images/woodgrove_taskpane_data.PNG)

![Надстройка, позволяющая анализировать направления расходных операций через WoodGrove Bank (панель мониторинга)] (../images/woodgrove_taskpane_dashboard.PNG)

![Надстройка, позволяющая анализировать направления расходных операций через WoodGrove Bank (средство отслеживания пожертвований)] (../images/woodgrove_taskpane_donations.PNG)

## Оглавление 

* [Необходимые компоненты](#prerequisites)
* [Запуск проекта](#run-the-project)
* [Дополнительные ресурсы](#additional-resources)

## Необходимые компоненты

Вам понадобится следующее:

* [Visual Studio 2015](https://www.visualstudio.com/downloads/download-visual-studio-vs.aspx).
* [Инструменты разработчика Office для Visual Studio](https://www.visualstudio.com/en-us/features/office-tools-vs.aspx).
* Excel 2016 версии не ниже 6769.2011.

## Запуск проекта

1. Скопируйте проект в локальную папку. Убедитесь, что путь к файлу не слишком длинный. В противном случае в Visual Studio может возникнуть ошибка при попытке установить пакеты NuGet, необходимые для проекта. 
2. Затем откройте файл `WoodGrove Expense Trends.sln` в Visual Studio. 
3. Нажмите клавишу F5, чтобы собрать и развернуть пример надстройки. Запустится приложение Excel 2016. В зависимости от его версии далее надстройка загрузит пользовательскую вкладку WoodGrove на ленте или откроется сама в области задач справа от листа, как показано на приведенных ниже рисунках.

![Надстройка, позволяющая анализировать направления расходных операций через WoodGrove Bank (исходная область задач)] (../images/woodgrove_taskpane_ribbon.PNG)

![Надстройка, позволяющая анализировать направления расходных операций через WoodGrove Bank (исходная область задач)] (../images/woodgrove_taskpane_import.PNG)

## Дополнительные ресурсы

* [Центр разработки для Office](http://dev.office.com/)

## Авторское право
(c) Корпорация Майкрософт (Microsoft Corporation), 2016. Все права защищены.


