FROM ossrs/srs:1.0.beta

ADD transcode.conf /etc/transcode.conf

CMD mkdir -p /data/root/live && \
    mkdir -p /data/log/transcode && \
    srs -c /etc/transcode.conf

VOLUME ["/data"]
EXPOSE 1935

