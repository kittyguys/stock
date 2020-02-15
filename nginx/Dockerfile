FROM nginx:latest

WORKDIR /root

COPY default.conf /etc/nginx/conf.d/default.conf

COPY . .

CMD [ "./wait-for-it.sh", "client:3000" ]
