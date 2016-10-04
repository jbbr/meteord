FROM debian:jessie
MAINTAINER Janek Thomaschewski

ENV METEORD_DIR /opt/meteord
COPY scripts $METEORD_DIR

RUN bash $METEORD_DIR/init.sh

EXPOSE 80
CMD bash $METEORD_DIR/run_app.sh
