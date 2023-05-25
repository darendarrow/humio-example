FROM humio/humio:1.88.0

ENV HUMIO_JVM_ARGS=-Xss2M -XX:MaxDirectMemorySize=4G
VOLUME ["/mnt/data:/data"]

COPY humio.conf /etc/humio/
