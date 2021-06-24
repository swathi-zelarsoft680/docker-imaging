FROM        ubuntu
RUN         apt update -y
RUN         apt install nginx -y
CMD         ["nginx", "-g", "daemon off;"]
ADD         index.html  /usr/share/nginx/html/index.html
