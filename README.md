# DragonBot

## Установка
1) Установка vkbottle 2:
   
   Последний стабильный релиз vkbottle:
   ```sh
   pip install vkbottle==2.7.8
   ```
   или
    ```sh
   pip install https://github.com/timoniq/vkbottle/archive/v2.0.zip --upgrade
   ```
2) Установка PIL:
   ```sh
   pip install pillow
   ```
3) Установка MySql:
   ```sh
   pip install PyMySQL
   ```
4) Установка Django:
   ```sh
   pip install Django
   ```

> Минимальная версия python для комфортной работы - 3.8


### Документация

Для начала работы нужно создать проект Django с помощью команды:
```sh
   django-admin startproject project_name
```
Далее переходим в папку проекта и создаем 2 приложения для работы с кейсами и для работы с пользователями
   >Приложение для кейсов:
   ```sh
      django-admin startapp web
   ```
   >Приложение для пользователей:
   ```sh
      django-admin startapp users
   ```
