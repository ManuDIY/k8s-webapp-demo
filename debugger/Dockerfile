FROM alpine
LABEL version="v1"
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
  && apk --no-cache add lynx \
  && apk --no-cache add git
CMD sh -c "while true; do sleep 15; done"
