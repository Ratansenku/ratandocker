FROM ubuntu
RUN apt update 
RUN apt install nginx -y
ADD index.html /var/www/html
ADD https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_3x4.jpg /var/www/html/billo.jpg
RUN chmod 644 /var/www/html/billo.jpg
CMD nginx -g 'daemon off;'