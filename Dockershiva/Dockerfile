FROM ubuntu
RUN apt update && apt install nginx -y
WORKDIR /var/www/html/
ADD index.html .
ADD https://i.pinimg.com/564x/9b/33/a0/9b33a0fefe98161ed2d8100dd1951b97.jpg shiva.jpg
RUN chmod 644 shiva.jpg
CMD nginx -g 'daemon off;'


