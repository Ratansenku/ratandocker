FROM ubuntu
RUN apt update 
RUN apt install nginx -y
ADD index.html /var/www/html
ADD https://img.freepik.com/free-vector/flat-golden-circle-balloons-birthday-background_52683-34659.jpg?size=626&ext=jpg&ga=GA1.1.553209589.1713744000&semt=ais /var/www/html/happyb.jpg
RUN chmod 644 /var/www/html/happyb.jpg
CMD nginx -g 'daemon off;'