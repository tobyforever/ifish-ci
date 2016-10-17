FROM nginx
MAINTAINER linmingzhe "tobyforever.lin@gmail.com"

# COPY run.sh /run.sh
# RUN chmod +x /run.sh

#COPY ./dist-fe-ui /usr/share/nginx/html
#COPY ./dist-fe-admin /usr/share/nginx/html/admin
COPY ./mysite.conf /etc/nginx/conf.d/default.conf
# CMD ["/run.sh"]

EXPOSE 80