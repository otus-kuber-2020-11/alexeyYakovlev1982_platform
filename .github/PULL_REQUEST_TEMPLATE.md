# Выполнено ДЗ №

 - [+] Основное ДЗ
 - [-] Задание со *

## В процессе сделано:
 - Основное ДЗ, в том числе - собран docker image с простым python http server, 
   опубликован - alexeyyakovlev1982/docker_simple_py_http_server_yakovlev
 - 

## Как запустить проект:
 - Run: 
     kubectl apply -f web-pod.yaml
     kubectl port-forward --address 0.0.0.0 pod/web 8000:8000
       

## Как проверить работоспособность:
 - Check:
   Run:
     kuberctl get pods -n default
     kuberctl describe pod web -n default
   Open via browser:
     http://localhost:8080/index.html

## PR checklist:
 - [ ] Выставлен label с темой домашнего задания