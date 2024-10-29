FROM mysql:latest

ADD dist/ /root/dist/

RUN mv /root/dist/init.sql /docker-entrypoint-initdb.d/init.sql
