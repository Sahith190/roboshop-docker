FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
COPY roboshop.config /etc/nginx/default.d/roboshop.config
ADD static /usr/share/nginx/html