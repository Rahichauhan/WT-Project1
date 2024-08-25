FROM httpd:2.4
COPY . /usr/local/apache2/htdocs/
EXPOSE 9000

RUN sed -i 's/Listen 80/Listen 9000/g' /usr/local/apache2/conf/httpd.conf