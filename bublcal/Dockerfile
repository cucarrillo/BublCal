FROM python:3.8

RUN pip install django whitenoise

COPY . .

CMD [ "python", "manage.py", "runserver" , "0.0.0.0:8000" ]
