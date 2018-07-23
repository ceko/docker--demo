FROM phusion/baseimage:0.10.1

COPY usr /usr
RUN apt-get update && \
    apt-get install -y unbound nginx

ENTRYPOINT [ "/usr/local/bin/entrypoint" ] 
CMD [ "start" ]