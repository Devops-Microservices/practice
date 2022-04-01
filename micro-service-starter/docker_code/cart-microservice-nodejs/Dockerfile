FROM node:8.1.1-alpine

LABEL MAINTAINER shrayansh jha <shrayansh.jha@capgemini.com>

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 1004

CMD ["node","index.js"]
