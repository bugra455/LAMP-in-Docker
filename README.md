# LAMP-in-Docker
A docker setup for using LAMP without installing XAMPP because it requires admin rights... 

Just put the DockerFile and docker-compose.yml into root of your project and run ` docker compose up --build -d `

Project tree should look like this:
```
THE IMPORTANT PROJECT NAME (Probably Hello World)
├── mysql-data/
└── src/
    ├── index.php
├── docker-compose.yml
└── Dockerfile
```
