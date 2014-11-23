from dockerfile/java

RUN wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.4.0.tar.gz && \
    tar -xzvf ./elasticsearch-1.4.0.tar.gz && \
    mv ./elasticsearch-1.4.0 /opt/elasticsearch && \
    rm ./elasticsearch-1.4.0.tar.gz

CMD ["/opt/elasticsearch/bin/elasticsearch"]
