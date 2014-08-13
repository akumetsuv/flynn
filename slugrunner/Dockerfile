FROM flynn/cedarish

RUN apt-get update && \
 apt-get install -y libicu-dev

ADD ./runner/ /runner
ADD ./bin/sdutil /bin/sdutil


ENTRYPOINT ["/runner/init"]
