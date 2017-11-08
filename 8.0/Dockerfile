FROM kkarczmarczyk/node-yarn:8.0

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli && \
    apt-get install -y ruby ruby-dev && \
    gem install --no-rdoc --no-ri sass -v 3.4.22 && \
    gem install --no-rdoc --no-ri compass

WORKDIR /workspace
