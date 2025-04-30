# https://hub.docker.com/_/drupal/

FROM drupal:10-apache

# https://github.com/docker-library/docs/blob/master/php/README.md#how-to-install-more-php-extensions

# https://stackoverflow.com/a/50121691
RUN apt-get update && \
    apt-get install --yes libxml2-dev && \
    docker-php-ext-install soap

# # https://github.com/docker-library/docs/blob/master/php/README.md#pecl-extensions
