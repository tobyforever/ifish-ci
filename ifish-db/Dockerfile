FROM java
MAINTAINER linmingzhe "tobyforever.lin@gmail.com"

ENV VERSION 1.0

COPY run.sh /run.sh
RUN chmod +x /run.sh

COPY ifish.jar /ifish.jar

CMD ["/run.sh"]

EXPOSE 8080