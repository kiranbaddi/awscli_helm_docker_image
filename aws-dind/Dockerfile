FROM jpetazzo/dind
RUN apt-get update -y && apt-get install python python-pip -y && \
    pip install awscli
ENTRYPOINT [ "/bin/bash" ]
