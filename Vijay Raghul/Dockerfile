# Use a base image with a web server (nginx in this case)
FROM nginx:alpine

# Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Copy your project files into the container
COPY . .

# Expose port 80 (default for HTTP)
EXPOSE 80

# Start the web server
CMD ["nginx", "-g", "daemon off;"]
