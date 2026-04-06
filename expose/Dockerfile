FROM    almalinux
RUN     dnf install nginx -y 
        #rm -rf usr/share/nginx/html/index.html
EXPOSE  80
COPY    index.html /usr/share/nginx/html
CMD     ["nginx", "-g", "daemon off;"]


