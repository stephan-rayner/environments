# PROJECT_DIR := ../../work

build:
	docker-compose build

down:
	docker-compose down

up:
	docker-compose up -d

open:
	open `docker-compose logs | grep http://localhost | tr " " "\n" | grep http://localhost`
ps:
	docker-compose ps

logs:
	docker-compose logs

restart: down build up open
