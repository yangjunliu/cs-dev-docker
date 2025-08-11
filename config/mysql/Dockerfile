FROM mysql:8.0.40-debian
COPY ./initdb.d/*.sql /docker-entrypoint-initdb.d/
# RUN chmod +x /docker-entrypoint-initdb.d/init.sh