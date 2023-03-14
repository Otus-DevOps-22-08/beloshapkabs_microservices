# beloshapkabs_microservices
beloshapkabs microservices repository

---
#### Лекция №31
1. Ingress Controller
2. Ingress
3. Secret
4. TLS
5. LoadBalancer Service
6. Network Policies
7. PersistentVolumes
8. PersistentVolumeClaims


---
#### Лекция №30
1. Развернули локальное окружение для работы с Kubernetes
2. Развернули Kubernetes в Yandex Cloud
3. Запустили reddit в Kubernetes

---
#### Лекция №28
1. Подготовили окружение
2. Подготовили инсталляцию Gitlab CI
3. Подготовили репозиторий с кодом приложения
4. Описали для приложения этапы пайплайна
5. Определили окружения

---
#### Лекция №25
1. Подготовили окружение
2. Залогировали Docker-контейнеры
3. Собрали неструктурированные логи
4. Визуализация логов
5. Собрали структурированные логи
6. Распределенный трейсинг с помощью zipkin

---
#### Лекция №22
1. Prometheus: запуск, конфигурация, знакомство с Web UI
2. Мониторинг состояния микросервисов
3. Сбор метрик хоста с использованием экспортера
4. Запушили собранные нами образы на DockerHub: https://hub.docker.com/repositories/beloshapkabs


---
#### Лекция №19
1. Разобрались с работой сети.
2. Собрали и запустили образ приложения с помощью docker-compose
3. Параметризовали некоторые переменные для docker-compose
4. Имя проекта можно задать с помощью ключа -p project_name
5. Создали файл docker-compose.override.yml
6. Запустили:
```
docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d
```

---
#### Лекция №18
1. Научились описывать и собирать Docker-образы для сервисного приложения.
2. Научились оптимизировать работу с Docker-образами.
3. Запуск и работа приложения на основе Docker-образов, оценка удобства запуска контейнеров при помощи docker run

---
#### Лекция №17

1. Создали docker host
2. Создали образ
3. Работа с Docker Hub
