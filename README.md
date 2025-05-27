# n8n_Docker
Развертывание платформы в Docker.

Основная команда для запуска:
docker-compose up

Для запуска в фоновом режиме (демон):
docker-compose up -d
   
Просмотр запущенных контейнеров:
docker-compose ps

Просмотр логов:
docker-compose logs

Для конкретного сервиса:
docker-compose logs -f ваш_сервис

Остановка контейнеров:
docker-compose down

Если нужно пересобрать образы
docker-compose up --build
