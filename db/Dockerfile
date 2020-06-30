FROM mysql:5.7
COPY . .
ADD CreateTable.sql /docker-entrypoint-initdb.d
EXPOSE 3306
ENTRYPOINT ["docker-entrypoint.sh"]
