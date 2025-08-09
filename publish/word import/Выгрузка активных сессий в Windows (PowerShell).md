_Статья базы знаний_

# #107 Выгрузка активных сессий в Windows (PowerShell) Описание

**Выгрузка активных сессий в Windows (PowerShell)**

Небольшой скрипт PowerShell, который выгружает из журналов Windows историю всех RDP и локальных подключений. В полученной таблице указано время подключения, имя пользователя, рабочая станция и IP адрес клиента. Информация по следующим событиям **EventID:21,23,24,25.** (при необходимости вы можете включить в отчет другие типы входов).

- Расположение скрипта: \\emh\store\ОИТ\Knowledgebase> **RDPConnectionParser**
- Запускаем скрипт, вводим hostname (дата по умолчанию установлена на 01.01.2023)

![Выгрузка активных сессий в Windows (PowerShell)](<Выгрузка активных сессий в Windows (PowerShell).jpeg>) ![Выгрузка активных сессий в Windows (PowerShell)](<Выгрузка активных сессий в Windows (PowerShell) 1.jpeg>)

Рис. 1 Рис. 2

![Выгрузка активных сессий в Windows (PowerShell)](<Выгрузка активных сессий в Windows (PowerShell) 2.jpeg>)

**Рис. 3**

- Как видно выше на рисунке №3, выгрузка осуществляется на рабочий стол пользователя.
- Открываем выгруженный файл и анализируем логи.

![Выгрузка активных сессий в Windows (PowerShell)](<Выгрузка активных сессий в Windows (PowerShell) 3.jpeg>)

**_События EventID_**

Рис. 4

- **EventID –** 21 (Remote Desktop Services: Session Logon Succeeded) означает успешный вход в сеанс.
- **EventID –** 22 (Remote Desktop Services: Shell start notification received) означает успешный запуск оболочки Explorer (появление окна рабочего стола в RDP сессии). отключение пользователя.
- **EventID –** 23 (Remote Desktop Services: Session logoff succeeded). Logoff – выход пользователя из

системы.

- **EventID –** 24 (Remote Desktop Services: Session has been disconnected) – пользователь отключился от RDP сессии.
- **EventID –** 25 (Remote Desktop Services: Session reconnection succeeded) – пользователь переподключился к своей имеющейся RDP сессии на сервере.
    1. **Просмотр событий входа пользователей в ПК LogonIP**

Выгрузка логов: **\\emh\LogonIP**

![Выгрузка активных сессий в Windows (PowerShell)](<Выгрузка активных сессий в Windows (PowerShell) 4.jpeg>)![Выгрузка активных сессий в Windows (PowerShell)](<Выгрузка активных сессий в Windows (PowerShell) 5.jpeg>)

поиск осуществляется по hostname ПК или определенному IP.

# Решение Обходной путь Файлы

_Опубликовал: Конаков Андрей Андреевич Дата публикации: 24.05.2023 13:11 Раздел базы знаний: Технические статьи Тип статьи: Вопрос-ответ_