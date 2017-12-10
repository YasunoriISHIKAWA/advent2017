FROM nginx:1.13.7

ADD ./nginx.conf /etc/nginx/nginx.conf
RUN rm /etc/nginx/conf.d/default.conf
ADD ./conf.d/ /etc/nginx/conf.d
