FROM ubuntu
RUN apt update && apt install nginx -y
WORKDIR /var/www/html/
ADD index.html .
ADD https://i.pinimg.com/originals/cf/45/57/cf4557befe282b4a02d2493a9cf9e3f8.jpg vishnu.jpg
RUN chmod 644 vishnu.jpg
CMD nginx -g 'daemon off;'


