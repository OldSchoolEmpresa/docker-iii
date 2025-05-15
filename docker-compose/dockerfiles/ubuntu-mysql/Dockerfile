FROM ubuntu:latest

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y mysql-server && \
    apt-get clean



    EXPOSE 3306


    CMD ["mysqld"]