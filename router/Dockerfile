FROM nginx
RUN rm -f /etc/nginx/conf.d/*
COPY test.conf /etc/nginx/conf.d/test.conf
CMD nginx -g 'daemon off;'