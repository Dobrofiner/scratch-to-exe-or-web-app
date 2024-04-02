# for-scratch-to-exe-or-web-app
<BR>Russian:Это новый уникальный способ превращения web приложения в exe. Для scratch перейдите в <a href="https://packager.turbowarp.org/">Turbowarp</a> и сконвертируйте ваш проект в exe(обязательно переменуйте %scratch-project%.html в index.html.
<BR>English:This is a new unique way to turn a web application into an exe. For scratch, go to <a href="https://packager.turbowarp.org/">Turbowarp</a> and convert your project to html(be sure to change%scratch-project%.html in index.html ).
<BR>Russian:
<BR>1.Подготовка:
<BR>Скачайте <a href="https://github.com/Dobroposter/scratch-to-exe-or-web-app">этот</a> репозиторий.
<BR>2.Распаковка и Настройка:
<BR>Установите Notepad++ для редактирования текста, Falco Icon Studio для создания иконок и Resource Hacker для редактирования ресурсов.(Все установщики в репозитории, resource hacker в папке resource_hacker)
<BR>Распакуйте архив forscratchtoexe.7z в желаемое место.
<BR>Переименуйте папку в соответствии с названием вашего приложения.
<BR>В каждой папке переименуйте внутренний .exe файл, используя имя вашего приложения.
<BR>3.Работа с Веб-Контентом:
<BR>Откройте папку www в каталогах x86 и x64.
<BR>Поместите файлы вашего веб-приложения в эту папку.
<BR>4.Создание Иконок:
<BR>Используйте Falco Icon Studio для создания иконок размером 128x128 и 256x256 пикселей с именами icon-128.png и icon-256.png.
<BR>Разместите иконки в папке icons внутри x64\www и x86\www.
<BR>5.Интеграция Иконок:
<BR>Используйте программу для создания иконок, чтобы сформировать иконку размером 256 пикселей.
<BR>Включите в иконку изображения меньших размеров до 32 пикселей для поддержки различных разрешений.
<BR>6.Редактирование Исполняемого Файла:
<BR>Откройте исполняемый файл в программе для редактирования.
<BR>Добавьте раздел иконок и назначьте созданную иконку в пустой ресурс.
<BR>7.Настройка package.json:
<BR>Отредактируйте файл package.json, изменив name приложения, имя окна и, при необходимости, разрешение экрана.
<BR>8.Завершение:
<BR>Проверьте все изменения и убедитесь, что приложение работает корректно.
<BR>PROFIT! Теперь ваше веб-приложение готово к использованию в виде .exe файла.
<BR>English:
<BR>1. Preparation:
<BR>Download <a href="https://github.com/Dobroposter/scratch-to-exe-or-web-app">this</a> repository.
<BR>2. Unpacking and Setup:
<BR>Install Notepad++ for text editing, Falco Icon Studio for creating icons, and Resource Hacker for editing resources. (All installers are in the repository,  but resource hacker in resource_hacker dir)
<BR>Unpack the forscratchtoexe.7z archive to the desired location.
<BR>Rename the folder according to the name of your application.
<BR>In each folder, rename the internal .exe file using the name of your application.
<BR>3. Working with Web Content:
<BR>Open the www folder in the x86 and x64 directories.
<BR>Place the files of your web application in this folder.
<BR>4. Creating Icons:
<BR>Use Falco Icon Studio to create icons sized 128x128 and 256x256 pixels with the names icon-128.png and icon-256.png.
<BR>Place the icons in the icons folder inside x64\www and x86\www.
<BR>5. Integrating Icons:
<BR>Use an icon creation program to create an icon sized 256 pixels.
<BR>Include images in the icon of smaller sizes down to 32 pixels to support different resolutions.
<BR>6. Editing the Executable File:
<BR>Open the executable file in the editing program.
<BR>Add an icon section and assign the created icon to an empty resource.
<BR>7. Setting up package.json:
<BR>Edit the package.json file, changing the application name, window name, and if necessary, screen resolution.
<BR>8. Completion:
<BR>Check all changes and ensure that the application works correctly.
<BR>PROFIT! Now your web application is ready for use as an .exe file.
