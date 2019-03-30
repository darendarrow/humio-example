FROM humio/humio:1.5.4

ENV HUMIO_JVM_ARGS=-Xss2M -XX:MaxDirectMemorySize=4G
VOLUME ["/mnt/data:/data"]

COPY humio.conf /etc/humio/
