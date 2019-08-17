FROM python:3.6-slim

RUN mkdir /app
WORKDIR /app
COPY . /app
RUN pip install -U pip && \
    pip install pipenv && \
    pipenv install --system --ignore-pipfile --deploy
