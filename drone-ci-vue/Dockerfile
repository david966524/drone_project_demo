FROM 172.30.0.6/test/nginx

COPY .docker-compose/nginx/conf.d/my.conf /etc/nginx/conf.d/my.conf
#WORKDIR /drone/src/
#RUN  ls -al
RUN  ls -al  /drone/src/dist/
COPY /dist  /usr/share/nginx/html
RUN cat /etc/nginx/nginx.conf
RUN cat /etc/nginx/conf.d/my.conf
RUN ls -al /usr/share/nginx/html
