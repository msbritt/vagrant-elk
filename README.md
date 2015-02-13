# Vagrant - ELK Stack

This is a vagrant stack to build and test various ELK environments.


## Starting Elasticsearch

	sudo docker run -d -p 9200:9200 -p 9300:9300 -v /vagrant/data:/data dockerfile/elasticsearch /elasticsearch/bin/elasticsearch -Des.config=/data/elasticsearch/elasticsearch.yml
