FROM node:16

WORKDIR /app

COPY . .

RUN npm i && npm run build && mkdir -p /var/www/html && mv build/* /var/www/html

WORKDIR /

RUN rm -rf /app 