FROM nginx:1.19-alpine
COPY ./docker/nginx/default.conf /etc/nginx/conf.d/default.conf
RUN mkdir -p /work/public
COPY ./public /work/public