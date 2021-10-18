FROM postgres:9.6-alpine
COPY ./configuration/postgresql/initdb/ /docker-entrypoint-initdb.d/
RUN chown postgres:postgres /docker-entrypoint-initdb.d/*.sh