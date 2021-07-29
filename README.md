# docker-guacamole-mariadb



## Запуск
1. Скачать с сайта https://guacamole.apache.org/releases/ нужный релиз архив guacamole-auth-jdbc-*.tar.gz. 
2. После распаковки из папки mysql скопировать в папку iniddb файлы 001-create-schema.sql и 002-create-admin-user.sql
3. Внести в  docker-compose.yml свои настройки
4. 
```bash
docker-compose up -d
```


    
        
