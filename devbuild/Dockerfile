#FROM meteorhacks/meteord:base
FROM registry.git.artos-hosting.de/janek/meteord
MAINTAINER Janek Thomaschewski

ONBUILD RUN bash $METEORD_DIR/lib/install_meteor.sh
ONBUILD COPY ./ /app
ONBUILD RUN bash $METEORD_DIR/lib/build_app.sh
