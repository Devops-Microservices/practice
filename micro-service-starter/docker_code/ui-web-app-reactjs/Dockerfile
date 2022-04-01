FROM node:8.1.1-alpine

LABEL maintainer="shrayansh"

WORKDIR /app
COPY . .

#RUN npm install cross-env
RUN npm install

EXPOSE 8080

CMD ["npm", "start"]
