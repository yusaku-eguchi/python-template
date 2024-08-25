FROM python:3.11

ENV PYTHONDONTWRITEBYTECODE=1

RUN mkdir  /src
WORKDIR /src

COPY docker/python/requirements.txt  /src
RUN apt update -y \
    && pip3 install -r requirements.txt