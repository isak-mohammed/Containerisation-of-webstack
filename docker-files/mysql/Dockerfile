FROM mysql:5.7.25

LABEL "Project"="containerisation_of_webstack"
LABEL "Author"="Isak"

ENV MYSQL_ROOT_PASSWORD="admin123"
ENV MYSQL_DATABASE="accounts"

ADD backend-repo/db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql