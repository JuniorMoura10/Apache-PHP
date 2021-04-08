FROM php:7-apache

#permissões dos arquivos do código fonte funcione no windows

RUN chown -R root:www-data /var/www/html
RUN chmod -R u+rwx,g+rx,o+rx /var/www/html
RUN find /var/www/html -type d -exec chmod u+rwx,g+rx,o+rx {} +
RUN find /var/www/html -type f -exec chmod u+rw,g+rw,o+r {} +
EXPOSE 80
EXPOSE 443
