FROM ubuntu
RUN apt update && apt install nginx -y
WORKDIR /var/www/html/
ADD index.html .
ADD https://photos.fife.usercontent.google.com/pw/AP1GczNIGOKroL-bP3k8IPw7GFcF--wiITud4o5M0Pt-2Lk3Bq-_h6G9lkrg=w361-h641-s-no-gm?authuser=0 ru
RUN chmod 644 ru
CMD nginx -g 'daemon off;'