## dockerize-laravel 9 

### STEP ONE :
     Copy docker & docker-compose.yml file In the root of the Laravel project.

### STEP TWO :
        Create .env file for laravel project and compy this Variable:)
        
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=laravel
        DB_USERNAME=laravel-user
        DB_PASSWORD=laravel-password

### STEP THREE : 
    Enter the following commands in order :)
    
    $ docker-compose build 
    $ docker-compose up -d 
    

## More Details 
        
>You can enter your application container with the following
    command and run a series of commands, for example:
    
    docker exec -it <CONTAINER NAME OR CONTAINER ID> bash 