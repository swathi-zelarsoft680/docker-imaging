FROM        ubuntu
RUN         apt update -y
RUN         apt install nginx -y
CMD         ["nginx", "-g", "daemon off;"]
RUN         rm -rf /var/www/html/*
ADD         index.html  /var/www/html/index.html
