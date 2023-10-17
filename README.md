## Запуск проекта
сделано только первое обязательное задание

создаем образ  docker build . --tag=docker_first_hw

запускаем контейнер  docker run -d -p 8080:80 --name=nginx_new docker_first_hw 

проверяем, что приветственная надпись поменялась curl localhost:8080