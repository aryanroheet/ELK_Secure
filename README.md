# ELK_Secure

Elasticsearch, Kibana and Logstash via docker

create directory t2s-stack under root directory Download docker-compose.yml file in t2s-stack directory if you want to mount kibana.yml and elasticsearch.yml outside the container so create a following directory

Kibana
Elasticsearch
Logstash 
The Tree structure looks like root
t2s-stack
  . Certs
    . Kibana.crt
    . Kibana.key
  . docker-compose.yml
  . Kibana
    . kibana -kibana.yml
  . logstash
    . pipeline
      . logstash.conf
  . Elasticsearch
    . elasticsearch.yml
