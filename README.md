# XXXX

├── README.md
├── docker-compose.yml
└── services
    ├── db
    │   ├── Dockerfile
    │   └── create.sql
    ├── nginx
    │   ├── Dockerfile
    │   └── prod.conf
    └── web
        ├── Dockerfile
        ├── manage.py
        ├── project
        │   ├── __init__.py
        │   ├── api
        │   │   ├── main.py
        │   │   ├── models.py
        │   │   └── users.py
        │   └── config.py
        └── requirements.txt

https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uswgi-and-nginx-on-ubuntu-18-04
