# ELK_Secure

Elasticsearch, Kibana and Logstash via docker

create directory t2s-stack under root directory Download docker-compose.yml file in t2s-stack directory if you want to mount kibana.yml and elasticsearch.yml outside the container so create a following directory

Kibana
Elasticsearch
Logstash 
The Tree structure looks like root
t2s-stack
  1. Certs
    . Kibana.crt
    . Kibana.key
  2. docker-compose.yml
  3. Kibana
    . kibana -kibana.yml
  4. logstash
    . pipeline
      . logstash.conf
  5. Elasticsearch
    . elasticsearch.yml
