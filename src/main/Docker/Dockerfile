# Use the official MySQL image from the Docker Hub
FROM mysql:latest

# Set environment variables for the MySQL root password and database name
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=ecommerce
ENV MYSQL_USER=root
ENV MYSQL_PASSWORD=root

# Expose the MySQL port
EXPOSE 3306

# Optionally, you can copy SQL scripts to initialize the database
# COPY init.sql /docker-entrypoint-initdb.d/
