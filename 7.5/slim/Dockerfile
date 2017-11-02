FROM kkarczmarczyk/node-yarn:7.5-slim

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli && \
    apt-get install -y ruby && \
    apt-get build-dep -y --force-yes ruby-compass && \
    gem install compass

WORKDIR /workspace