# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:6.4.0

RUN NODE_OPTIONS="--max-old-space-size=4096" kibana-plugin install \
https://download.elastic.co/kibana/canvas/kibana-canvas-0.1.2174.zip
# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
