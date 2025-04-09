# Use an official MySQL image as a base
FROM mysql:5.7

# Set environment variables for MySQL configuration
ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=video_db

COPY init.sql /docker-entrypoint-initdb.d/


# Expose MySQL port
EXPOSE 3306
