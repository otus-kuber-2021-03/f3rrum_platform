FROM nginx:latest
WORKDIR /app
RUN usermod -u 1001 nginx
ADD default.conf /etc/nginx/conf.d/
EXPOSE 8000
