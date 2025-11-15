## проект по django "Запись на тестдрайв"
Проект представляет собой сайт из трех страниц с функцией записи на тест драйв
На главной страцине отображаются записи
<img width="794" height="402" alt="image" src="https://github.com/user-attachments/assets/143f071e-28cf-4807-ae7a-ed7362cda583" />
Страница "О компании"
<img width="1528" height="695" alt="image" src="https://github.com/user-attachments/assets/2cee8f43-70b8-45b2-862f-3a96f3fe69bb" />
Для записи на тестдрайв нужно перейти на страницу "Тестдрайв" и нажать отправить.
<img width="733" height="141" alt="image" src="https://github.com/user-attachments/assets/bda2768a-b151-4be1-939c-6220ed1f5d28" />
После заполнение тесдрайва  и после отправки появляется новая таблица с данными
## Руководство програмиста
> Django — это высокоуровневый Python веб-фреймворк для быстрой разработки безопасных и поддерживаемых веб-сайтов.
Начало с работой со средой
```
# Создаю вирт. среду.
python -m venv .venv
# Активирую вирт. среду.
.venv\Scripts\activate
# Устанавливаю библиотеку
python -m pip install Django
# Перехожу в папке проекта
cd testdrive
# Создаю приложение 
python manage.py startapp hello
# Перейдите в файл settings.py и аразделе INSTALLED_APPS  впишите название приложения 
# Запускаем
python manage.py runserver
```
