FROM ubuntu:18.04

ADD entrypoint.sh /entrypoint.sh
RUN apt-get update && apt-get -qq -y install wget
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
