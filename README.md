# Docker LNMP

Docker stack running nginx, PHP-FPM, MySQL, phpMyAdmin.

| Server     | Version | Port |
|------------|------|------|
| nginx      | 1.14 | 80   |
| PHP-FPM    | 7.2  | 9000 |
| MySQL      | 5.7  | 3306 |
| phpMyAdmin | 4.8  | 3636 |


## Getting started

1. Create `.env` file out of `.env.example`
2. Start the containers:
````
docker-compose up -d
```` 
3. Access your project ([http://localhost:80](http://localhost:80)) or phpMyAdmin ([http://localhost:3636](http://localhost:3636)).

## Docker commands

### Stop the containers
````
docker-compose down
```` 
### Use bash on container
````
docker exec -it <container_name> bash
```` 