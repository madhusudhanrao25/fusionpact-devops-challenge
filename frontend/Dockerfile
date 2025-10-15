FROM nginx:alpine

RUN rm -f /usr/share/nginx/html/*

COPY Devops_Intern.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
