FROM docker.elastic.co/elasticsearch/elasticsearch:7.9.1

RUN bin/elasticsearch-plugin install analysis-nori
RUN cd /usr/share/elasticsearch/config
RUN mkdir userdict_ko.txt