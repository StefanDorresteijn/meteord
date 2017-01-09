FROM stefandorresteijn/meteord:base
MAINTAINER MeteorHacks Pvt Ltd.

ONBUILD USER deploy
ONBUILD COPY ./ /app
ONBUILD RUN bash $METEORD_DIR/on_build.sh
