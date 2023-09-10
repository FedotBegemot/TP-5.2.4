# TP-5.2.4
## Проект "UnivTimetable"
[Ссылка на apk для скачивания](https://github.com/FedotBegemot/TP-5.2.4/blob/main/app-debug.apk)
### Ссылки на репозитории:
- **[Сервер](https://github.com/tukitoki/UnivTimeTable-backend)**
- **[Клиент](https://github.com/iIlyaM/UnivTimeTable)**

### Выполняют студенты 5.2:

1. **[Свиридов Фёдор](https://github.com/FedotBegemot) - Тестирование, документация**

2. **[Молдавский Илья](https://github.com/iIlyaM) - Клиентская часть**

3. **[Распопов Павел](https://github.com/tukitoki) -  Серверная часть, развертка**

### Тема: Приложение для составления университетского расписания с учётом вместительности и занятости аудиторий.

#### Особенности проекта:
- [X] Уведомление старост по электронной почте об изменениях в расписании, то есть староста будет знать, 
какие занятия на неделе у его группы были перенесены, а преподаватель будет иметь возможность перенести занятия на то время, 
которое ему будет удобным.
- [X] Заявки от преподавателей по их свободному времени. То есть преподаватель имеет право подать заявку на составление расписания
с учетом того времени, когда ему будет неудобно проводить ту или иную пару.
- [X] Импорт расписания в таблицу (отдельно для группы или преподователя).
----
### Документация:

- **[Swagger](https://timetable-service-tukitoki.cloud.okteto.net/api/timetable/swagger-ui/index.html)**
- **[Документация](https://github.com/FedotBegemot/TP-5.2.4/tree/main/%D0%94%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F)**
- **[Техническое задание](https://github.com/FedotBegemot/TP-5.2.4/blob/main/%D0%94%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F/%D0%A2%D0%97.pdf)**
- **[Диаграммы](https://github.com/FedotBegemot/TP-5.2.4/tree/main/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B)**
- **[Курсовая работа](https://github.com/FedotBegemot/TP-5.2.4/blob/main/%D0%94%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F/%D0%9A%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0.pdf)**
- **[Презентация](https://github.com/FedotBegemot/TP-5.2.4/blob/main/%D0%94%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F/%D0%9F%D1%80%D0%B5%D0%B7%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F%20UnivTimetable.pptx)**
- **[Сопроводительное письмо](https://github.com/FedotBegemot/TP-5.2.4/blob/main/%D0%94%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F/%D0%A1%D0%BE%D0%BF%D1%80%D0%BE%D0%B2%D0%BE%D0%B4%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5%20%D0%BF%D0%B8%D1%81%D1%8C%D0%BC%D0%BE.pdf)**
----
### Видео
- **[Видео с разверткой приложения](https://drive.google.com/file/d/1rNxTRaGGJJ9GSQZN18S5ubT-92ooTjml/view?usp=sharing)**
- **[Видео с обзором серверной части](https://drive.google.com/file/d/1inpzktzGy71LYXlpLfpjdgTwy7ueqlbL/view?usp=sharing)**
- **[Видео с обзором клиентской части](https://disk.yandex.ru/i/xJyqRyPNcHHXgg)**
- **[Видео с обзором работы приложения](https://youtu.be/yq1IhHU8ydc)**
- **[Видеопрезентация проекта](https://youtu.be/Ukrr0Sgoo5k)**
- **[Видеопрезентация ко 2-ой аттестации](https://youtu.be/xL2jRJXNqe0)**
------
### Сервисы
- **[Miro](https://miro.com/app/board/uXjVPhSKaX0=/?share_link_id=911852827355)**
- **[Trello](https://trello.com/b/Q9oCXbbY/%D1%81%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D1%80%D0%B0%D1%81%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D1%8F)**
- **[Figma](https://www.figma.com/file/m2anmNcEu5ZxfiYcXzP4Pk/UnivTimeTable?node-id=0-1&t=TBJTWewhOpbanF8w-0)**
---
### Данные для входа в приложение

**Для работы с защищенными в swagger методами необходимо вставить
тестовые данные в эндпоинт /auth/login Auth API, взять оттуда accessToken 
и вставить его в Authorize сверху страницы или нажав на замочек рядом с методом.**

**Администратор:**
- Почта: tokichiihere@gmail.com
- Пароль: admin

**Первый преподаватель**
- Почта: imoldavskiy@yandex.ru
- Пароль: lecturer

**Второй преподаватель**
- Почта: fedorsviridov@gmail.com
- Пароль: lecturer

**Староста**
- Почта: vadim02101@gmail.com
- Пароль: headman
