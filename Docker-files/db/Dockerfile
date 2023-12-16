FROM mysql:8.0.32
LABEL "Project"="Vprofile"
LABEL "Author"="Romi"

ENV MYSQL_ROOT_PASSWORD="vprodpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql