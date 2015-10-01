# docker-elasticsearch
Docker ElasticSearch

Usage
------

	docker run -d -p 9200:9200 duruu/elasticsearch

	docker run -d -it -p 9200:9200 -e ELASTICSEARCH_USER=admin -e ELASTICSEARCH_PASS=admin --name es duruu/elasticsearch