FROM nginx


RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
COPY soundauth.crt /etc/ssl
COPY soundauth.key /etc/ssl
COPY ca.crt /etc/ssl