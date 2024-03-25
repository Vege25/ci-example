FROM mariadb:latest

# Copy initialization script to the container
COPY create-db.sql /docker-entrypoint-initdb.d/

# Environment variables for MariaDB
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=ASMdb
ENV MYSQL_USER=db2_user
ENV MYSQL_PASSWORD=db2_password

# Expose the MariaDB port
EXPOSE 3306

