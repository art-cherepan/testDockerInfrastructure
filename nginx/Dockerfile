FROM nginx:1.19.8-alpine

COPY ./hosts/mysite.local.conf /etc/nginx/conf.d

WORKDIR /data  

VOLUME /data  

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
