# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.4.3
EXPOSE 12201/udp

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

# Gelf plugin
RUN logstash-plugin install logstash-input-gelf