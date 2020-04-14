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

**1. Configuração do ambiente virtual**

Faça o clone do repositório:

`git clone https://github.com/reno/django_rest_api.git`

Crie um ambiente virtual:

`python3 -m venv venv`

Ative o ambiente virtual:

`source venv/bin/activate`

Instale as dependências no ambiente virtual:

`pip install -r requirements.txt`
