# app/Dockerfile.python
FROM python:3.9-alpine

WORKDIR /var/www

COPY requirements.txt /var/www/requirements.txt

RUN apk add --no-cache git && \
    pip install --no-cache-dir -r requirements.txt


CMD ["tail", "-f", "/dev/null"]
