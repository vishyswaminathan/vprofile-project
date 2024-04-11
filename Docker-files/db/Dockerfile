FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Vishy"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql