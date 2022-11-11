FROM openjdk:8-jre

MAINTAINER evafelipecontacto@gmail.com

RUN mkdir -p /usr/local/app

WORKDIR /usr/local/app

COPY drop/ordering-service-0.1.0.jar usr/local/app/

COPY drop/run.sh usr/local/app/run.sh


COPY drop/application.properties application.properties


EXPOSE 8080

ENTRYPOINT sh usr/local/app/run.sh
