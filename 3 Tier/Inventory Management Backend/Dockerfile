FROM mysql:8.0

# Set environment variables
ENV MYSQL_ROOT_PASSWORD=rootpassword123


# Copy init script into MySQL auto-run directory
COPY mysqldump.sql /docker-entrypoint-initdb.d/

# Optional: custom config
# COPY my.cnf /etc/mysql/conf.d/

EXPOSE 3306
