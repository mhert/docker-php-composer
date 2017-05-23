# docker-php-composer

A docker image to run composer(https://getcomposer.org/)

## Usage 

    docker run -u ${UID}:${GID} -v ${PWD}:/src -w /src mhert/php-composer install
