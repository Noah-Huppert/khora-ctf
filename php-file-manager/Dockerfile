FROM nginx:1.19.9

RUN apt-get update && apt-get install -y unzip

# Download file
RUN mkdir -p /opt/php-file-manager
WORKDIR /opt/php-file-manager

RUN mkdir -p /var/www/
