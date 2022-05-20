# minio

Minio + nginx + letsenrypt

## Getting started

0. mv example.env .env && mv example.docker-compose.yml docker-compose.yml
1. Fill variables in .env file
2. Execute docker-compose up -d certbot
3. Execute init.letsencrypt.sh {YOUR_HOST}, where {YOUR_HOST} is equals to FQDN variable in .env file.
4. docker-compose up -d 
5. MinioConsole: https://{YOUR_HOST}:443/ , MinioApi: ttps://{YOUR_HOST}:9000/