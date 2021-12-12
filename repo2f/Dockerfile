FROM python:3.9.9-alpine

WORKDIR /app

COPY requirements.txt /app

RUN pip3 install -r requirements.txt --no-cache-dir 

COPY . /app

EXPOSE 2564

CMD python src/manage.py runserver 0.0.0.0:2564