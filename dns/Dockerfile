FROM phusion/baseimage:0.10.1

RUN apt-get update && \
    apt-get install -y unbound

COPY usr /usr
COPY etc /etc

ENTRYPOINT [ "/usr/local/bin/entrypoint" ] 
CMD [ "start" ]