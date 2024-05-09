FROM ubuntu
RUN apt update && apt install nginx -y
WORKDIR /var/www/html/
ADD index.html .
ADD https://static.javatpoint.com/top10-technologies/images/top-10-beautiful-girls-in-india.png bolly.png
RUN chmod 644 bolly.png
CMD nginx -g 'daemon off;'
