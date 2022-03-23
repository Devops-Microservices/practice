FROM maven AS build

MAINTAINER Shrayansh

WORKDIR /app

COPY . .

RUN mvn clean install


FROM openjdk:12

WORKDIR /app
COPY --from=build /app/target/offers-0.0.1-SNAPSHOT.jar /app

EXPOSE 1001

CMD ["java","-jar","offers-0.0.1-SNAPSHOT.jar"]