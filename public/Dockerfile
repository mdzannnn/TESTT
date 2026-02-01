# Use a lightweight web server (Green IT friendly!)
FROM nginx:alpine

# Copy your conversion app files into the web server's directory
# This matches your repo structure seen in public/
COPY ./public /usr/share/nginx/html

# Open port 80 so we can see the app in a browser
EXPOSE 80

# Start the web server
CMD ["nginx", "-g", "daemon off;"]
