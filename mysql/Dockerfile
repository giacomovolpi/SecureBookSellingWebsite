FROM mysql:8.2.0

ENV MYSQL_ROOT_PASSWORD=rootroot
ENV MYSQL_DATABASE=securebooksellingdb

COPY dump.sql /docker-entrypoint-initdb.d/dump.sql

EXPOSE 3306
