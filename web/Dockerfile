FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY roboshop.conf /etc/nginx/conf.d/roboshop.conf
COPY static /usr/share/nginx/html/