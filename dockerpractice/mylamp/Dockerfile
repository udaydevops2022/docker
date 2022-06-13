FROM ubuntu:focal
LABEL author="uday"
RUN export DEBIAN_FRONTEND=noninteractive && apt update && apt install apache2 -y 
EXPOSE 80
ADD start.sh /start.sh
CMD ["/bin/bash", "-c", "/start.sh"]