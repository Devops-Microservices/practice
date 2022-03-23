FROM node:slim

LABEL MAINTAINER shrayansh jha <shrayansh.jha@capgemini.com>

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 1004

CMD ["node","index.js"]