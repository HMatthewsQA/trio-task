FROM mysql
RUN CREATE DATABASE flask-db;
RUN use flask-db;
COPY . .
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
EXPOSE 3306

