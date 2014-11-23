from dockerfile/java

RUN wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.4.0.tar.gz && \
    tar -xzvf ./elasticsearch-1.4.0.tar.gz && \
    mv ./elasticsearch-1.4.0 /opt/elasticsearch && \
    rm ./elasticsearch-1.4.0.tar.gz

RUN /opt/elasticsearch/bin/plugin -i royrusso/elasticsearch-HQ && /opt/elasticsearch/bin/plugin -i lmenezes/elasticsearch-kopf

CMD ["/opt/elasticsearch/bin/elasticsearch"]
