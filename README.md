# Тестовое задание на Junior DevOps для Михаила
1. Ansible
   
Задание: настройка сервера с помощью Ansible для OS Ubuntu 18.04, с использованием ролей в соответствии с лучшими практиками.

Роли:

a. Написать роль Ansible, которая установит на хост 5 выбранных пакетов (например: nmap, traceroute, vim и т.д.)

> Выполненное задание находится в ansible/roles/packages_and_dns

b. Настроить DNS-серверы для хоста: 8.8.8.8, 1.1.1.1

> Выполненное задание находится в ansible/roles/packages_and_dns

c. Написать роль Ansible, которая установит на хост ELK-стек из дефолтного файла docker-compose, используя модуль docker_containers и шаблоны для настройки конфигураций.

> Выполненное задание находится в ansible/roles/elk-stack

<hr>

2. Kubernetes

a. Написать приложение на Python, которое будет слушать порт 8080 и обрабатывать входящие запросы.

> Выполненное задание находится в python_app/

b. Упаковать это приложение в Docker и загрузить его на Docker Hub.

> Выполненное задание находится в python_app/

c. Написать Helm-чарт для развертывания этого приложения в Kubernetes, включая ингрес (любой домен) и монтирование директории на узле кластера.

> Не выполнено
