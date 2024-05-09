FROM ubuntu
RUN apt update && apt install nginx -y
WORKDIR /var/www/html/
ADD index.html .
ADD https://thumbs.dreamstime.com/b/cute-pic-radhe-krishna-zula-river-art-mode-cute-pic-radhe-krishna-zula-river-304371771.jpg radhekrishna.jpg
RUN chmod 644 radhekrishna.jpg
CMD nginx -g 'daemon off;'
