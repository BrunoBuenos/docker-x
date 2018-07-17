# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:6.3.0
RUN bin/logstash-plugin install logstash-input-jdbc
RUN bin/logstash-plugin install logstash-filter-date
RUN bin/logstash-plugin install logstash-filter-mutate
RUN bin/logstash-plugin install logstash-filter-geoip

#ADD pipeline/ /usr/share/logstash/pipeline/
#ADD config/ /usr/share/logstash/pipeline/jdbc
COPY teste.jar /tmp/teste.jar
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
