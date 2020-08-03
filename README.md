# redis

 ## New Redis from Docker.
 > sudo docker run -p 16379:6379 -d redis:6.0 redis-server --requirepass "password#"
 
 ## Docker CLI
 > sudo docker exec -it 646332e1088f sh  
 > redis-cli  
 > AUTH password#  
 > SET name Maduranga  
 > GET name  

 
 
Resources
https://www.journaldev.com/18141/spring-boot-redis-cache
https://www.devglan.com/spring-boot/spring-boot-redis-cache
