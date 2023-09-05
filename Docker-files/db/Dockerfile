FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "Author"="huncho"

ENV MYSQ_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-init.d/db_backup.sql