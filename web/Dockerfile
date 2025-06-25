FROM nginx 
RUN rm -rf usr/share/nginx/index.html
COPY static  /usr/share/nginx/html 
RUN rm -rf /etc/nginx/default.d/roboshop.conf 
ADD /etc/nginx/default.d/roboshop.conf 