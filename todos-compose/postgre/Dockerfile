FROM postgres

COPY ./init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432

# olivercw/todopostgre
# docker build -t olivercw/todopostgre .