FROM bitnami/kafka:latest

RUN mkdir -p /opt/bitnami/kafka/plugins && \
    cd /opt/bitnami/kafka/plugins
CMD /opt/bitnami/kafka/bin/connect-distributed.sh /bitnami/kafka/config/connect-distributed.properties