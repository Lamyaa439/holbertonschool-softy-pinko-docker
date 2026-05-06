# Use the latest Nginx image
FROM nginx:latest

# Copy the front-end static files to the Nginx html directory
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the custom Nginx config to overwrite the default
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
