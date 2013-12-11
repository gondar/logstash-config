logstash-config
===============

The logstash configurations

QA machines 10.10.20.68, 10.10.20.42, 10.10.20.86.  10G memory, 4 CPUs, 1T space for ES.

Prod machines: 10.20.23.64, 10.20.23.65.  8G and 16G memory, 8 CPUs, 213G space for ES

Uk Prod machines: 192.168.220.241 (logstash -> redis <- logstash ->), 192.168.220.242 (elasticsearch), 192.168.220.243 (<- kibana only). 8G memory 27G space, 16G memory 310G space, 1G memory 9G space

Redis:
NA: logstash
UK: logstash-apievent
