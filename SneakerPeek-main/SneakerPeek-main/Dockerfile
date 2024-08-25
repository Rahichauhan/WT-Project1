FROM nginx:alpine

# Copy your application files to the NGINX default root directory
COPY . /usr/share/nginx/html

# Expose port 8000 to match the original Apache configuration
EXPOSE 8000

# Override the default NGINX configuration to listen on port 8000
CMD ["nginx", "-g", "daemon off;"]
