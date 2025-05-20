# Use NGINX base image
FROM nginx:alpine

# Remove default NGINX page
RUN rm -rf /usr/share/nginx/html/*

# Copy all files into NGINX web root
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX (already default in base image, included here for clarity)
CMD ["nginx", "-g", "daemon off;"]