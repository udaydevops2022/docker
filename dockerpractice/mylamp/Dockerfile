FROM ubuntu:focal
LABEL name="uday"
RUN export DEBIAN_FRONTEND=noninteractive && apt update && apt install apache2 && service start apache2.service
EXPOSE 80
CMD ["sleep", "1d"]
