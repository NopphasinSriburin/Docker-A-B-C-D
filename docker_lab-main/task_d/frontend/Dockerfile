# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy the static files to the Nginx HTML directory
COPY . /usr/share/nginx/html

# Expose the port Nginx will serve on
EXPOSE 80

# No CMD needed as Nginx will start by default