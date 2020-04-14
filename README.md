# Django REST API 

## Estrutura da aplicação

O projeto é organizado conforme abaixo:

```
/django_rest_api/scrum/
.
├── board
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── serializers.py
│   ├── tests.py
│   └── views.py
├── manage.py
├── scrum
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
└── └── wsgi.py
```

## Uso

Faça o clone do repositório:

`git clone https://github.com/reno/django_rest_api.git`

Crie um ambiente virtual:

`python3 -m venv venv`

Ative o ambiente virtual:

`source venv/bin/activate`

Instale as dependências no ambiente virtual:

`pip install -r requirements.txt`

Inicialize o banco de dados:

`createdb -E UTF-8 scrum`

Inicialize o servidor de desenvolvimento:

`python manage.py runserver`

Finalmente, acesse o servidor para navegar pela API:

`http://127.0.0.1:8000/api/`



