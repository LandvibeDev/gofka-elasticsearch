# LOCAL ELASTICSEARCH SETTING

### docker run

```shell
docker-compose up -d --build
```



### docker info

#####  - master Elasticserach

- version : 6.8.3
- ES_JAVA_OPTS : -Xms512m -Xmx512m

#####  - data Elasticserach

- version : 6.8.3
- ES_JAVA_OPTS : -Xms1024m -Xmx1024m

#####  - coordinator Elasticserach

- version : 6.8.3
- ES_JAVA_OPTS : -Xms512m -Xmx512m

#####  - kibana

- version : 6.8.3



### helthcheck

```
curl http://localhost:9200/_cluster/health?pretty=true
curl localhost:9200/_cat/health?v
curl localhost:9200/_cat/nodes?v
```



 