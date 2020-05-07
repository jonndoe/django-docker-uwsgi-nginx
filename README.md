This is sample project configuration for development of django apps
using docker.

to run for development:
 git clone https://github.com/jonndoe/django-docker-uwsgi-nginx.git
 cd django-docker-uwsgi-nginx
 mkdir dbdata
 docker-compose up --build
 
to run for "production":
 git clone https://github.com/jonndoe/django-docker-uwsgi-nginx.git
 cd django-docker-uwsgi-nginx
 mkdir dbdata
 docker-compose -f docker-compose.prod.yml up --build