 

# Сбой при открытии ссылок (из outlook, excel и т.п.)

Материал из omegawiki

[Перейти к навигации](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)#mw-head) [Перейти к поиску](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)#searchInput)

## Содержание

- [1 Способ №1](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)#%D0%A1%D0%BF%D0%BE%D1%81%D0%BE%D0%B1_%E2%84%961)
- [2 Способ №2](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)#%D0%A1%D0%BF%D0%BE%D1%81%D0%BE%D0%B1_%E2%84%962)
    - [2.1 Проверить ветку реестра:](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)#%D0%9F%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%B8%D1%82%D1%8C_%D0%B2%D0%B5%D1%82%D0%BA%D1%83_%D1%80%D0%B5%D0%B5%D1%81%D1%82%D1%80%D0%B0:)
    - [2.2 Импорт раздела реестра](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)#%D0%98%D0%BC%D0%BF%D0%BE%D1%80%D1%82_%D1%80%D0%B0%D0%B7%D0%B4%D0%B5%D0%BB%D0%B0_%D1%80%D0%B5%D0%B5%D1%81%D1%82%D1%80%D0%B0)

### Способ №1[[править](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=edit&section=1 "Редактировать раздел «Способ №1»")]

Редактор реестра (regedit) запускаем от имени пользователя!

  

При открытии ссылок (из outlook, excel и т.п.) получаем ошибку:

**Эта операция была прервана из-за ограничений, наложенных на данный компьютер. Обратитесь к системному администратору.** Проблема может возникнуть после использования Google Chrome.

В ветках реестра:

- HKEY_CLASSES_ROOT \.htm

- HKEY_CLASSES_ROOT \.html

Параметр «по умолчанию» выставляем в значение **htmlfile**

  

[![](./Сбой%20при%20открытии%20ссылок%20(из%20outlook,%20excel%20и%20т.п.)%20—%20omegawiki_files/Htmlfile.png)](http://10.1.115.172:8080/mediawiki/index.php/%D0%A4%D0%B0%D0%B9%D0%BB:Htmlfile.png)

Перезапускаем сбойное приложение, проверяем ошибку.

  

### Способ №2[[править](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=edit&section=2 "Редактировать раздел «Способ №2»")]

Если данная процедура не исправила проблему обращаемся к ОБХОДНОМУ ПУТИ.

#### Проверить ветку реестра:[[править](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=edit&section=3 "Редактировать раздел «Проверить ветку реестра:»")]

KEY_LOCAL_MACHINE\Software\Classes\htmlfile\shell\open\command

Если ветка отсутствует, его необходимо добавить в ручном режиме по аналогии с другим АРМ либо выполнить экспорт/импорт:

1. На компьютере, где подобная проблема возникает, нажмите Пуск>Выполнить.
2. В поле Открыть введите regedit и нажмите кнопку ОК.
3. Найдите и выделите следующий подраздел реестра: HKEY_LOCAL_MACHINE\Software\Classes\htmlfile\shell\open\command.
4. В меню Файл или Реестр (в зависимости от операционной системы) выберите Экспорт.
5. Запишите расположение для сохранения файла.
6. Введите уникальное имя файла, затем нажмите Сохранить.
7. Закройте редактор реестра.

#### Импорт раздела реестра[[править](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=edit&section=4 "Редактировать раздел «Импорт раздела реестра»")]

- Скопируйте экспортированный раздел реестра на рабочий стол компьютера с проблемой.
- Дважды щелкните REG-файл.

Появится следующее сообщение:

**Windows 10, Windows 8.1 и Windows 8**

Добавление сведений может привести к непреднамеренному изменению или удалению значений и неправильной работе компонентов. Если вы не доверяете источнику этой информации в папке C:Users<yourlogon>Desktop\regkey.reg, не добавляйте его в реестр.

Последовательно нажмите Да>OK

  
Перезапускаем сбойное приложение, проверяем ошибку, проверяем ошибку. **Если проблема сохраняется, назначаем заявку на вторую линию.**

Источник — [http://10.1.115.172:8080/mediawiki/index.php?title=Сбой_при_открытии_ссылок_(из_outlook,_excel_и_т.п.)&oldid=165](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&oldid=165)

## Навигация

### Персональные инструменты

- Вы не представились системе
- [Обсуждение](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%9C%D0%BE%D1%91_%D0%BE%D0%B1%D1%81%D1%83%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5 "Страница обсуждений для моего IP [alt-shift-n]")
- [Вклад](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%9C%D0%BE%D0%B9_%D0%B2%D0%BA%D0%BB%D0%B0%D0%B4 "Список правок, сделанных с этого IP-адреса [alt-shift-y]")
- [Создать учётную запись](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D1%82%D1%8C_%D1%83%D1%87%D1%91%D1%82%D0%BD%D1%83%D1%8E_%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C&returnto=%D0%A1%D0%B1%D0%BE%D0%B9+%D0%BF%D1%80%D0%B8+%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8+%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA+%28%D0%B8%D0%B7+outlook%2C+excel+%D0%B8+%D1%82.%D0%BF.%29 "Мы предлагаем вам создать учётную запись и войти в систему, хотя это и не обязательно.")
- [Войти](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%92%D1%85%D0%BE%D0%B4&returnto=%D0%A1%D0%B1%D0%BE%D0%B9+%D0%BF%D1%80%D0%B8+%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8+%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA+%28%D0%B8%D0%B7+outlook%2C+excel+%D0%B8+%D1%82.%D0%BF.%29 "Здесь можно зарегистрироваться в системе, но это необязательно. [alt-shift-o]")

### Пространства имён

- [Статья](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\) "Просмотреть контентную страницу [alt-shift-c]")
- [Обсуждение](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%9E%D0%B1%D1%81%D1%83%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5:%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=edit&redlink=1 "Обсуждение основной страницы (страница не существует) [alt-shift-t]")

 русский

### Просмотры

- [Читать](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\))
- [Править](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=edit "Редактировать данную страницу [alt-shift-e]")
- [История](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=history "Журнал изменений страницы [alt-shift-h]")

 Ещё

### Поиск

   

[](http://10.1.115.172:8080/mediawiki/index.php/%D0%97%D0%B0%D0%B3%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F_%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0 "Перейти на заглавную страницу")

### Навигация

### Разделы

- [Работа с личными устройствами пользователей](http://10.1.115.172:8080/mediawiki/index.php/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0_%D1%81_%D0%BB%D0%B8%D1%87%D0%BD%D1%8B%D0%BC%D0%B8_%D1%83%D1%81%D1%82%D1%80%D0%BE%D0%B9%D1%81%D1%82%D0%B2%D0%B0%D0%BC%D0%B8_%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9)
- [СКУД](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%9A%D0%A3%D0%94)
- [РЕГИСТРАТУРА](http://10.1.115.172:8080/mediawiki/index.php/%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%82%D1%83%D1%80%D0%B0)
- [Почта](http://10.1.115.172:8080/mediawiki/index.php/%D0%9F%D0%BE%D1%87%D1%82%D0%B0)
- [Частые проблемы](http://10.1.115.172:8080/mediawiki/index.php/%D0%A7%D0%B0%D1%81%D1%82%D1%8B%D0%B5_%D0%BF%D1%80%D0%BE%D0%B1%D0%BB%D0%B5%D0%BC%D1%8B)
- [Служебные записки](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D1%8B%D0%B5_%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D0%BA%D0%B8)
- [Программное обеспечение](http://10.1.115.172:8080/mediawiki/index.php/%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)
- [Работа с АРМ](http://10.1.115.172:8080/mediawiki/index.php/%D0%A0%D0%B0%D0%B1%D0%BE%D1%82%D0%B0_%D1%81_%D0%90%D0%A0%D0%9C)

### Инструменты

- [Ссылки сюда](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B8_%D1%81%D1%8E%D0%B4%D0%B0/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\) "Список всех страниц, ссылающихся на данную [alt-shift-j]")
- [Связанные правки](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D0%B2%D1%8F%D0%B7%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5_%D0%BF%D1%80%D0%B0%D0%B2%D0%BA%D0%B8/%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\) "Последние изменения в страницах, на которые ссылается эта страница [alt-shift-k]")
- [Служебные страницы](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D0%BF%D0%B5%D1%86%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D1%8B "Список служебных страниц [alt-shift-q]")
- [Версия для печати](javascript:print\(\); "Версия этой страницы для печати [alt-shift-p]")
- [Постоянная ссылка](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&oldid=165 "Постоянная ссылка на эту версию страницы")
- [Сведения о странице](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%B1%D0%BE%D0%B9_%D0%BF%D1%80%D0%B8_%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B8_%D1%81%D1%81%D1%8B%D0%BB%D0%BE%D0%BA_\(%D0%B8%D0%B7_outlook,_excel_%D0%B8_%D1%82.%D0%BF.\)&action=info "Подробнее об этой странице")

- Эта страница в последний раз была отредактирована 29 июля 2024 в 16:11.

- [Политика конфиденциальности](http://10.1.115.172:8080/mediawiki/index.php/Omegawiki:%D0%9F%D0%BE%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0_%D0%BA%D0%BE%D0%BD%D1%84%D0%B8%D0%B4%D0%B5%D0%BD%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
- [О omegawiki](http://10.1.115.172:8080/mediawiki/index.php/Omegawiki:%D0%9E%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5)
- [Отказ от ответственности](http://10.1.115.172:8080/mediawiki/index.php/Omegawiki:%D0%9E%D1%82%D0%BA%D0%B0%D0%B7_%D0%BE%D1%82_%D0%BE%D1%82%D0%B2%D0%B5%D1%82%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D1%81%D1%82%D0%B8)

- [![Powered by MediaWiki](./Сбой%20при%20открытии%20ссылок%20(из%20outlook,%20excel%20и%20т.п.)%20—%20omegawiki_files/poweredby_mediawiki_88x31.png)](https://www.mediawiki.org/)