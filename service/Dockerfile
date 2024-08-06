FROM php:7.4-cli
LABEL "maintainer"="Evgenii Sopov <mrseakg@gmail.com>"
LABEL "repository"="https://github.com/sea-kg/ctf01d"

COPY ./src /service/app/
WORKDIR /service/app/
EXPOSE 4003

CMD [ "php", "-S", "0.0.0.0:4003"]

