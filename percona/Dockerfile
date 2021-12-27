FROM percona:5.7

LABEL maintainer="Vladlen Beilik <vladlen.beilik@gmail.com>"

RUN chown -R mysql:root /var/lib/mysql/

COPY my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306
