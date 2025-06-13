FROM ubuntu:22.04
RUN apt-get update && apt-get install -y curl
RUN apt-get install -y nginx
WORKDIR /var/www/html
COPY index.html .
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80
