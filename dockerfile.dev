# Use the official Nginx image from the Docker Hub
FROM nginx:alpine

# Copy all files from the current directory to the Nginx web server directory
COPY . /usr/share/nginx/html/

# Expose port 80 to access the web server
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]

