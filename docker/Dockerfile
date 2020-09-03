FROM alpine
RUN apk add --no-cace curl wget busybox-extras netcat-openbsd python py-pip busybox-extras&& \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
