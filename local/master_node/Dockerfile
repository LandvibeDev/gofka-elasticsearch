FROM docker.elastic.co/elasticsearch/elasticsearch:6.8.2
MAINTAINER Jeong Minkyo <redwonder@naver.com>


ADD jvm.options /usr/share/elasticsearch/config/
ADD elasticsearch.yml /usr/share/elasticsearch/config/
USER root
RUN chown elasticsearch:elasticsearch config/jvm.options config/elasticsearch.yml
USER elasticsearch
EXPOSE 9200 9300
