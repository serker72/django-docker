#Собрать отраз
docker-compose build

# Запустить контейнеры
docker-compose up -d

# Посмотреть контейнеры
docker ps

# Посмотреть log контейнера django-web
docker logs django-web

# Останвоить контейнеры
docker-compose down

# Просмотр сайта
http://localhost:8000/
