## === Makefile ===

help:				## | Show this help.
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/##//'

build:				## | Build the anaylsis environment with all need dependencies.
	docker-compose build

down:				## | Take the envrionment down and clean up
	docker-compose down

up:				## | Launch the environment
	docker-compose up -d

open:				## | Open Jupyter Notebook in a browser.
	open `docker-compose logs | grep http://localhost | tr " " "\n" | grep http://localhost`

ps:				## | View the running docker-compose processes
	docker-compose ps

logs:				## | View logs of the containers
	docker-compose logs

restart: down build up open 	## | Restart the environment