FROM postgres:14
ENV POSTGRES_USER postgres
ENV POSTGRES_DB etg
ENV POSTGRES_PASSWORD postgres


EXPOSE 5432

COPY data.sql /docker-entrypoint-initdb.d/