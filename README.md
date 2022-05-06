# Navigate.
1. Включить OpenServer и создать через _phpmyadmin_ базу данных с назвнием **db_videos** (кодировка *utf8_general_ci*)
3. В папкие **client** вызвать: **npm install**
4. В папке **server** вызвать: **npm install**
5. В папке **server** запустить сервер: **npm run dev**
6. Открыть еще одну консоль _(уже в папке client)_, вызвать npm **start**
7. Готово







_*Изменить инфу о бд на свои можно в файле .env (папка **server**)*_:

```
  PORT= "Порт на котором будет работать сервер (можно поставить 5000)"
  DB_NAME= "название вашей бд (в моем случае 'db_videos')"
  DB_USER= "имя юзера (в OpenServer по умолчанию 'root')"
  DB_PASSWORD= "пароль (в OpenServer по умолчанию его нету)"
  DB_HOST= "хост (в OpenServer по умолчанию 'localhost')" 
  DB_PORT= "порт хоста (в OpenServer по умолчанию '3306')" 
```
