FROM mysql:5.7
MAINTAINER w2w

ADD createGameTable.sql /docker-entrypoint-initdb.d

EXPOSE 3306
CMD ["mysqld"]


