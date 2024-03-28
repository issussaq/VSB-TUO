FROM postgres:15
LABEL maintainer='Miroslav Nekoranec <nm@mn.eu>'


COPY *.sql /docker-entrypoint-initdb.d/
COPY *.sh /docker-entrypoint-initdb.d/
