FROM ubuntu:22.04
RUN apt-get update
RUN apt-get -y install nginx=1.18.* tree
RUN echo "<marquee>Ola k ase</marquee>" > /var/www/html/index.html
EXPOSE 80
ENTRYPOINT [ "/usr/sbin/nginx", "-g", "daemon off;" ]
CMD [ "-g", "daemon off;" ]