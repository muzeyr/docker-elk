# docker-finds elk
Docker Elastic  Logstash Kibana



By default, the stack exposes the following ports:

* 5044: Logstash Beats input
* 50000: Logstash TCP input
* 9600: Logstash monitoring API
* 9200: Elasticsearch HTTP
* 9300: Elasticsearch TCP transport
* 5601: Kibana



```console
$ docker-compose up
```

```console
curl -XPOST http://localhost:9200/api/v1/clusters/elasticsearch/http://http://localhost:9200/proxy/{elasticsearch_path} \
-u elastic:uzeyr2022 \
-H X-Management-Request: 'test'
```