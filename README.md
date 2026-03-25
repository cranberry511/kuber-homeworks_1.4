## Решение задания 1

Создание Deployment приложения, состоящего из двух контейнеров:
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/deployment-multi-container.yaml
![Deployment](img/mynginx.jpg)

Создание Service типа ClusterIP:  
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/service-clusterip.yaml
![Service ClusterIP](img/mysvc.jpg)

Проверка доступности:
![Проверка доступности](img/curl1.jpg)

![Проверка доступности2](img/curl2.jpg)


Создание Service типа NodePort:
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/service-nodeport.yaml
![Service NodePort](img/mysvc2.jpg)

Проверка доступа:
![Проверка доступности3](img/curl3.jpg)


## Решение задания 2

Разворачивание двух Deployment:
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/deployment-frontend.yaml  
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/deployment-backend.yaml  
![Deployment2](img/deploy2.jpg)

Создание Service для каждого приложения:
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/service-frontend.yaml  
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/service-backend.yaml  
![Service2](img/svc2.jpg)

Создание Ingress:
https://github.com/cranberry511/kuber-homeworks_1.4/blob/main/ingress.yaml
![Ingress](img/ingress.jpg)

Проверка доступности:
![Проверка доступности4](img/curl4.jpg)

![Проверка доступности5](img/curl5.jpg)