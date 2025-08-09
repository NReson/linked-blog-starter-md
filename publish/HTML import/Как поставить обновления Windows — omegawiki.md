 

# Как поставить обновления Windows

Материал из omegawiki

[Перейти к навигации](http://10.1.115.172:8080/mediawiki/index.php/%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows#mw-head) [Перейти к поиску](http://10.1.115.172:8080/mediawiki/index.php/%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows#searchInput)

1. Ставим DNS (8.8.8.8 и 1.1.1.1)

[![](./Как%20поставить%20обновления%20Windows%20—%20omegawiki_files/PC4.png)](http://10.1.115.172:8080/mediawiki/index.php/%D0%A4%D0%B0%D0%B9%D0%BB:PC4.png)

2. Заходим в редактор реестра от **админа** по пути **Компьютер\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU**

В параметр **UseWUServer** ставим значение **0**

[![](./Как%20поставить%20обновления%20Windows%20—%20omegawiki_files/PC5.png)](http://10.1.115.172:8080/mediawiki/index.php/%D0%A4%D0%B0%D0%B9%D0%BB:PC5.png)

3. Открываем командную строку от **администратора** вводим команды

- **Net stop wuauserv**

- **Net start wuauserv**

4. Открываем центр обновления Windows и пробуем еще раз загрузить обновления

Источник — [http://10.1.115.172:8080/mediawiki/index.php?title=Как_поставить_обновления_Windows&oldid=301](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows&oldid=301)

## Навигация

### Персональные инструменты

- Вы не представились системе
- [Обсуждение](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%9C%D0%BE%D1%91_%D0%BE%D0%B1%D1%81%D1%83%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5 "Страница обсуждений для моего IP [alt-shift-n]")
- [Вклад](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%9C%D0%BE%D0%B9_%D0%B2%D0%BA%D0%BB%D0%B0%D0%B4 "Список правок, сделанных с этого IP-адреса [alt-shift-y]")
- [Создать учётную запись](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D1%82%D1%8C_%D1%83%D1%87%D1%91%D1%82%D0%BD%D1%83%D1%8E_%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C&returnto=%D0%9A%D0%B0%D0%BA+%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C+%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F+Windows "Мы предлагаем вам создать учётную запись и войти в систему, хотя это и не обязательно.")
- [Войти](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%92%D1%85%D0%BE%D0%B4&returnto=%D0%9A%D0%B0%D0%BA+%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C+%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F+Windows "Здесь можно зарегистрироваться в системе, но это необязательно. [alt-shift-o]")

### Пространства имён

- [Статья](http://10.1.115.172:8080/mediawiki/index.php/%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows "Просмотреть контентную страницу [alt-shift-c]")
- [Обсуждение](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%9E%D0%B1%D1%81%D1%83%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5:%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows&action=edit&redlink=1 "Обсуждение основной страницы (страница не существует) [alt-shift-t]")

 русский

### Просмотры

- [Читать](http://10.1.115.172:8080/mediawiki/index.php/%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows)
- [Править](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows&action=edit "Редактировать данную страницу [alt-shift-e]")
- [История](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows&action=history "Журнал изменений страницы [alt-shift-h]")

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

- [Ссылки сюда](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B8_%D1%81%D1%8E%D0%B4%D0%B0/%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows "Список всех страниц, ссылающихся на данную [alt-shift-j]")
- [Связанные правки](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D0%B2%D1%8F%D0%B7%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5_%D0%BF%D1%80%D0%B0%D0%B2%D0%BA%D0%B8/%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows "Последние изменения в страницах, на которые ссылается эта страница [alt-shift-k]")
- [Служебные страницы](http://10.1.115.172:8080/mediawiki/index.php/%D0%A1%D0%BB%D1%83%D0%B6%D0%B5%D0%B1%D0%BD%D0%B0%D1%8F:%D0%A1%D0%BF%D0%B5%D1%86%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D1%8B "Список служебных страниц [alt-shift-q]")
- [Версия для печати](javascript:print\(\); "Версия этой страницы для печати [alt-shift-p]")
- [Постоянная ссылка](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows&oldid=301 "Постоянная ссылка на эту версию страницы")
- [Сведения о странице](http://10.1.115.172:8080/mediawiki/index.php?title=%D0%9A%D0%B0%D0%BA_%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C_%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F_Windows&action=info "Подробнее об этой странице")

- Эта страница в последний раз была отредактирована 14 августа 2024 в 12:27.

- [Политика конфиденциальности](http://10.1.115.172:8080/mediawiki/index.php/Omegawiki:%D0%9F%D0%BE%D0%BB%D0%B8%D1%82%D0%B8%D0%BA%D0%B0_%D0%BA%D0%BE%D0%BD%D1%84%D0%B8%D0%B4%D0%B5%D0%BD%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
- [О omegawiki](http://10.1.115.172:8080/mediawiki/index.php/Omegawiki:%D0%9E%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5)
- [Отказ от ответственности](http://10.1.115.172:8080/mediawiki/index.php/Omegawiki:%D0%9E%D1%82%D0%BA%D0%B0%D0%B7_%D0%BE%D1%82_%D0%BE%D1%82%D0%B2%D0%B5%D1%82%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D1%81%D1%82%D0%B8)

- [![Powered by MediaWiki](./Как%20поставить%20обновления%20Windows%20—%20omegawiki_files/poweredby_mediawiki_88x31.png)](https://www.mediawiki.org/)