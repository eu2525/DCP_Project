FROM postgres

ENV POSTGRES_DB postgres
ENV POSTGRES_USER postgres
ENV POSTGRES_PASSWORD postgres

VOLUME [ "./image/postgres/data:/var/lib/mysql" ]
VOLUME [ "./image/postgres/mysqld:/var/run/mysqld" ]

EXPOSE 5432