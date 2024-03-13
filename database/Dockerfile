FROM postgres:latest

ENV POSTGRES_USER=root
ENV POSTGRES_PASSWORD=root
ENV POSTGRES_DB=root

VOLUME /postgres-data

EXPOSE 5432

ENTRYPOINT ["postgres", "-d"]
