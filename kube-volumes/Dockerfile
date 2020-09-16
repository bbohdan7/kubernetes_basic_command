FROM ubuntu:latest
RUN apt update ; apt install -y fortune
ADD fortuneloop.sh /bin/fortuneloop.sh
ENTRYPOINT /bin/fortuneloop.sh
