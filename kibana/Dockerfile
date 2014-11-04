from dockerfile/java

RUN wget https://download.elasticsearch.org/kibana/kibana/kibana-4.0.0-BETA1.1.tar.gz && \
    tar -xzvf ./kibana-4.0.0-BETA1.1.tar.gz && \
    mv ./kibana-4.0.0-BETA1.1 /opt/kibana && \
    rm ./kibana-4.0.0-BETA1.1.tar.gz

CMD ["/opt/kibana/bin/kibana"]
