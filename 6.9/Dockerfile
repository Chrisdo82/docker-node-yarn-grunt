FROM kkarczmarczyk/node-yarn:6.9

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli && \
    apt-get install -y ruby ruby2.1-dev ruby-compass && \
    gem install compass

WORKDIR /workspace