FROM postgis/postgis:16-3.4

WORKDIR /tmp/db

RUN mkdir /data && chown postgres /data

COPY schema.sql /docker-entrypoint-initdb.d/01.sql
