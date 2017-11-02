FROM kkarczmarczyk/node-yarn:7.5

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli && \
    apt-get install ruby && \
    gem install compass

WORKDIR /workspace