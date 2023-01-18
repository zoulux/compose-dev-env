FROM nginx:1.21

RUN sed -i 's/deb.debian.org/mirrors.aliyun.com/g' /etc/apt/sources.list &&\
    apt-get update &&\
    apt-get install -y git

COPY conf /etc/nginx/conf.d/default.conf
