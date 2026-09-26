FROM httpd:2.4-alpine

LABEL author="Adil" project="DEMODOCKER"

COPY . /usr/local/apache2/htdocs/

EXPOSE 80

