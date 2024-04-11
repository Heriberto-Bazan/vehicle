FROM nginx:1.19

ARG UID
EXPOSE $UID

RUN adduser -u ${UID} --disabled-password --gecos "" userapp

COPY default.conf /etc/nginx/conf.d