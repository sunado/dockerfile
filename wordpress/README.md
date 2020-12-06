## Wordpress docker
Install Docker + Docker-Compose + open port 80,443  
Edit your password, email, host in docker-compose.yml  
Edit your host in nginx/default.conf  
Run: docker-compose up -d  
Wait certbox finish -> your host is up in port 80  
Stop: docker-compose down  
Replace new config from template/afterSSL.conf   
Run again: docker-compse up -d  -> your host is get https  

