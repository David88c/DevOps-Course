FROM nginx:1.25.4-alpine3.18

WORKDIR /usr/src/app

COPY nginx.conf /etc/nginx/conf.d

COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
