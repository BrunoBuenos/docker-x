# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:6.4.0
RUN bin/logstash-plugin install logstash-input-jdbc
RUN bin/logstash-plugin install logstash-filter-date
RUN bin/logstash-plugin install logstash-filter-mutate
RUN bin/logstash-plugin install logstash-filter-geoip

# Add your logstash plugins setup here
COPY teste.jar /tmp/teste.jar

# Example: RUN logstash-plugin install logstash-filter-json
