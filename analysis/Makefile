# PROJECT_DIR := ../../work

build:
	docker-compose build

down:
	docker-compose down

up: build
	docker-compose up -d
	sleep 2
	open `docker-compose logs | grep http://localhost | tr " " "\n" | grep http://localhost`

ps:
	docker-compose ps

logs:
	docker-compose logs

restart: down up
