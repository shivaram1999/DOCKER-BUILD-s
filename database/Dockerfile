FROM mysql:latest
WORKDIR /var/lib/mysql
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306
