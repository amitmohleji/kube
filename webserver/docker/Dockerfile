FROM httpd:2.4-alpine
COPY ./html/ /usr/local/apache2/htdocs/
RUN echo "ServerName localhost" | tee /etc/apache2/conf-available/fqdn.conf
RUN a2enconf fqdn