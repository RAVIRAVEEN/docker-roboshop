FROM nginx 
RUN rm -rf usr/share/nginx/html/index.html
COPY static  /usr/share/nginx/html 
RUN rm -rf /etc/nginx/default.d/roboshop.conf 
ADD  roboshop.conf  /etc/nginx/default.d/roboshop.conf 