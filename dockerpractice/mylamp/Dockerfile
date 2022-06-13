FROM ubuntu:focal
LABEL name="uday"
RUN export DEBIAN_FRONTEND=noninteractive && apt update && apt install apache2 && service apache2 start
EXPOSE 80
CMD ["sleep", "1d"]
