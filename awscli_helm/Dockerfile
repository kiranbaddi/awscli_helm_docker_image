FROM akashkaveti/base_image:latest
RUN apk update && \
    apk add --no-cache --update python2 py-pip jq curl git docker  && \
    pip install awscli
CMD ["/bin/sh"]
