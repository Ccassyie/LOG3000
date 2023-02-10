FROM nginx:1.20.2-alpine
RUN apk update
RUN apk add git
RUN rm /usr/share/nginx/html/*
RUN git clone https://github.com/sZghab/LOG3000-Docker-TP.git /usr/share/nginx/html
EXPOSE 80