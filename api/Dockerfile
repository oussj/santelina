# Use an official PHP runtime as a parent image
FROM php:8.2-fpm-alpine

# Set working directory
WORKDIR /var/www/symfony

# Install system dependencies
RUN apk add --no-cache \
    acl \
    file \
    gettext \
    git \
    bash \
    curl \
    postgresql-dev # Add PostgreSQL dev tools for pgsql extension

# Install PHP extensions
RUN docker-php-ext-install pdo pdo_mysql pdo_pgsql # Add pdo_pgsql extension

# Install Composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

# Install Symfony CLI
RUN wget https://get.symfony.com/cli/installer -O - | bash \
    && mv /root/.symfony5/bin/symfony /usr/local/bin/symfony

# Copy the application's code to the container
COPY . /var/www/symfony

# Set permissions for Symfony
RUN chown -R www-data:www-data /var/www/symfony \
    && chmod -R 755 /var/www/symfony

# Expose port 8000 for the Symfony server
EXPOSE 8000

# Optionally set the Symfony environment to dev
ENV APP_ENV=dev

# Start Symfony server (uncomment if you want the container to start the server automatically)
# CMD ["symfony", "server:start", "--port=8000", "--no-tls", "--allow-http"]
