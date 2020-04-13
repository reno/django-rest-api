# Django REST API 

## Estrutura da aplicação

O projeto é organizado conforme abaixo:

```
/django_rest_api/scrum/
├── manage.py
├── scrum/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── board/
│   ├── migrations/
│   │   └── __init__.py
│   ├── __init__.py
│   ├── admin.py
│   ├── models.py
│   ├── tests.py
├── └── views.py
└── requirements.txt
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
