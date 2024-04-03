FROM ubuntu:latest
RUN apt-get update && apt-get upgrade -y
RUN mkdir  -p /soft/mysql
RUN mkdir /backup
RUN apt-get install openjdk-8-jdk -y
RUN apt-get install python3.10 -y
RUN apt-get install mysql-server -y
ENV MYSQL_ROOT_PASSWORD=root_password
ENV MYSQL_DATABASE=my_database
ENV MYSQL_USER=my_user