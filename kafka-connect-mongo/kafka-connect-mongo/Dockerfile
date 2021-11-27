FROM bitnami/kafka:2.8.1-debian-10-r31
# Download MongoDB&reg; Connector for Apache Kafka https://www.confluent.io/hub/mongodb/kafka-connect-mongodb
RUN mkdir -p /opt/bitnami/kafka/plugins && \
    cd /opt/bitnami/kafka/plugins 
COPY ./mongo-kafka-connect-1.6.1-confluent.jar /opt/bitnami/kafka/plugins/
CMD /opt/bitnami/kafka/bin/connect-standalone.sh /bitnami/kafka/config/connect-standalone.properties /bitnami/kafka/config/mongo.properties

