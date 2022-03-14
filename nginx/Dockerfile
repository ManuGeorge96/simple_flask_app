FROM nginx:alpine

WORKDIR /etc/nginx/conf.d

COPY ansible.devforfree.tech.conf .

CMD ["nginx", "-g", "daemon off;"]
