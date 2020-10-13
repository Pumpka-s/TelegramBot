# Thodos

## О программе
Тодос - телеграм бот, запоминающий задачи пользователя. Он способен создавать, изменять, удалять 

Чтобы воспользоываться ботом, перейдите по следующий ссылке https://t.me/pumpkabot

## Установка
### Скачивание
1. Склонируйте репозиторий с помощью команды `git clone https://github.com/Pumpka-s/TelegramBot.git`
2. Используйте `pip install -r requirements.txt` для установки необходимых библиотек
### Запуск
1. Введите команду `python bot.py` находясь в корне репозитория

## Работа с ботом
### Регистрация
Для начала работы с ботом, нажмите "Start", после бот зарегистрирует вас и вы можете мользоваться всеми его функциями.

### Создание туду
Чтобы создать туду, нажмите на "Новый туду", после чего бот отправит вам инструкцию по созданию:
В первой строке введите название вашего туду.
Во второй, и далее - описание

### Просмотр туду
Чтобы просмотреть туду, нажмите на "Мои туду", после чего бот отправит вам ваши туду, если они у вас есть.

### Изменение туду
Чтобы изменить туду, удалить или пометить сделанным, нажмите на "Мои туду", далее под нужным туду нажмите "Изменить", выберите параметр: "Перезаписать" или "Добавить" и введите текст
Параметр "Перезаписать" полностью заменяет ваше туду на тот, который вы введете.
Параметр "Добавить" добавит введенный текст в конец описания.

### Удаление аккаунта
Чтобы удалить аккаунт, введите команду `/delete_account`, после этого все ваши туду, и аккаунт будет удален без возможности восстановления.
