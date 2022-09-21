install:
	pip install --upgrade pip &&\
		pip install -r requirements.txt
freeze:
	pip freeze > requirements.txt
run:
	docker compose up -d &&\
	docker compose exec django_api python manage.py migrate
