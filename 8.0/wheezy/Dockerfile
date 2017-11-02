FROM kkarczmarczyk/node-yarn:8.0-wheezy

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli && \
    apt-get install -y ruby && \
    apt-get build-dep -y --force-yes ruby-compass && \
    gem install compass

WORKDIR /workspace
