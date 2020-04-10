FROM wordpress:latest

RUN apk add --no-cache tzdata

ENV WORDPRESS_DB_HOST databases
ENV WORDPRESS_DB_USER wp_root
ENV WORDPRESS_DB_PASSWORD wp_root_123
ENV WORDPRESS_DB_NAME wp_wp