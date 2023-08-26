# Use the official NGINX base image
FROM nginx:latest

# Copy custom configuration files to the container
COPY index.html /usr/share/nginx/html/
COPY script.js /usr/share/nginx/html/
COPY styles.css /usr/share/nginx/html/

# Expose the HTTP port
EXPOSE 80

# Start NGINX when the container runs
CMD ["nginx", "-g", "daemon off;"]
