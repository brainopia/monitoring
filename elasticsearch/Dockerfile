from dockerfile/java

RUN wget https://download.elastic.co/elasticsearch/elasticsearch/elasticsearch-1.7.1.tar.gz && \
    tar -xzvf ./elasticsearch-1.7.1.tar.gz && \
    mv ./elasticsearch-1.7.1 /opt/elasticsearch && \
    rm ./elasticsearch-1.7.1.tar.gz

RUN /opt/elasticsearch/bin/plugin -i royrusso/elasticsearch-HQ && /opt/elasticsearch/bin/plugin -i lmenezes/elasticsearch-kopf/1.5.7

CMD ["/opt/elasticsearch/bin/elasticsearch"]
