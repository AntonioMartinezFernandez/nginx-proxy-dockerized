FROM httpd:alpine3.18

RUN apk update

COPY index.html /usr/local/apache2/htdocs/index.html
COPY build /usr/local/apache2/htdocs/build