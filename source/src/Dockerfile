FROM python:3.6.4-alpine3.7

RUN pip install Flask

WORKDIR /usr/src/flaskapp
COPY ./app.py ./
CMD python app.py
