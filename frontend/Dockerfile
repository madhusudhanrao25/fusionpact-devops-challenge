FROM nginx:alpine

# Remove default Nginx index page
RUN rm -f /usr/share/nginx/html/*

# Copy your HTML file as index.html
COPY Devops_Intern.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
