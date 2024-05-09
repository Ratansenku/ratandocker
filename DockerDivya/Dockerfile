FROM ubuntu
RUN apt update 
RUN apt install nginx -y
ADD index.html /var/www/html
ADD https://i.pinimg.com/originals/8c/2a/e9/8c2ae9beb88415d85d715c38f1593115.jpg /var/www/html/divya.jpg
RUN chmod 644 /var/www/html/divya.jpg
CMD nginx -g 'daemon off;'