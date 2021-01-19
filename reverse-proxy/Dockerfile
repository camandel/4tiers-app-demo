FROM nginx:stable-alpine
COPY default.conf /etc/nginx/conf.d
WORKDIR /usr/share/nginx/html
EXPOSE 80
CMD ["/bin/sh", "-c", "exec nginx -g 'daemon off;';"]
