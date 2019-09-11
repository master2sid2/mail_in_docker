FROM    alpine:3.10.2

RUN     apk add --update php-fpm \
                         php7-curl \
                         php7-gd \
                         php7-mbstring \
                         php7-mcrypt \
                         php7-mysqlnd \
			 php7-xml \
			 php7-xmlrpc \
                         php7-pdo_mysql \
                         php7-mysqli

COPY    files/www.conf /etc/php7/php-fpm.d/
WORKDIR /var/www/

EXPOSE  9000
CMD     php-fpm7 -F -R
