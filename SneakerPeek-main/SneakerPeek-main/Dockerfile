# Use the official Nginx image from the Docker Hub
FROM nginx:alpine

# Set the working directory to Nginx's default directory for HTML files
WORKDIR /usr/share/nginx/html

# Copy the HTML project files to the Nginx default directory
COPY . .

# Expose port 80 to access the web server
EXPOSE 80

# Nginx runs automatically in this image, so no need to specify CMD
