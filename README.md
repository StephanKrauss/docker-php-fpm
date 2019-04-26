# PHP-FPM docker image with composer
# Fork !!! Original by camilb/docker-php-fpm

```ready for laravel and cakePHP frameworks ```



ImageLayers : [![](https://badge.imagelayers.io/camil/php-fpm:latest.svg)](https://imagelayers.io/?images=camil/php-fpm:latest)


## Info

* Based on php:5.6-fpm official Image [php:5.6-fpm](https://hub.docker.com/_/php/)

        

## Build

For example, if you need to install or remove php extensions, edit the Dockerfile and than build-it.

	git clone https://github.com/StephanKrauss/docker-php-fpm.git
	cd ./docker-php-fpm
	docker build --rm -t camil/php-fpm .

## Usage

	docker pull stephanKrauss/php-fpm
	docker run --rm -d stephanKrauss/php-fpm


