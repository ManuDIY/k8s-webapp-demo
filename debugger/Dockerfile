FROM alpine
LABEL version="v0"
LABEL author="Ansil H"
LABEL maintainer="ansilh@gmail.com"
RUN apk update \
  && apk --no-cache add ca-certificates \
  && update-ca-certificates \
  && apk --no-cache add openssl \
  && apk --no-cache add curl \
  && apk --no-cache add wget \
  && apk --no-cache add bind-tools \
  && apk --no-cache add netcat-openbsd \
  && apk --no-cache add lynx
CMD sh -c "while true; do sleep 15; done"
