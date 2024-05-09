FROM ubuntu
RUN apt update && apt install nginx -y
WORKDIR /var/www/html/
ADD index.html .
ADD https://img.freepik.com/premium-vector/vishwaroopa-darshanam-lord-krishna-hindu-religion_586724-199.jpg vishnu.jpg
RUN chmod 644 vishnu.jpg
CMD nginx -g 'daemon off;'


