# Dockerized Wordpress
_____________

### Initial setup
Create all containers required
- RUN : 
`docker-compose up -d`

### Stop application
Stop containers but preserve all changes made botn on files and database
- RUN :
`docker-compose stop`

### Start application
Start containers bringing back everything that was stop
- RUN :
`docker-compose start`

### Destroy application
Delete containers, network created, volumes created and database.
You will need todo initial setup again to bringup everything again
- RUN :
`docker-compose down -v`

### Access your application
> http://localhost

### Access your Database (PhpMyAdmin)
- host : 127.0.0.1:8080
- username : root
- password : root
- database name : wordpress