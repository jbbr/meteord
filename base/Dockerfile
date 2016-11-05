FROM debian:jessie
MAINTAINER Janek Thomaschewski

ENV METEOR_WAREHOUSE_URLBASE https://d3fm2vapipm3k9.cloudfront.net
ENV METEORD_DIR /opt/meteord
COPY scripts $METEORD_DIR

RUN bash $METEORD_DIR/init.sh

EXPOSE 80
CMD bash $METEORD_DIR/run_app.sh
