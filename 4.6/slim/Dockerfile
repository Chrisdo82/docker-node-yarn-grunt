FROM kkarczmarczyk/node-yarn:4.6-slim

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli && \
    apt-get install ruby && \
    gem install compass

WORKDIR /workspace