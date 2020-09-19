# Use the official image as a parent image.
FROM httpd:latest

# Set the working directory.
WORKDIR /usr/local/apache2

# Copy the file from your host to your current location.
COPY httpd.conf /usr/local/apache2/conf/

# Run the command inside your image filesystem.
RUN apt-get update && apt-get install nano && mkdir htdocs/web
