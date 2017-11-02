FROM kkarczmarczyk/node-yarn:4.3.2-slim

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli && \
    apt-get install -y ruby ruby-compass && \
    gem install compass
    
WORKDIR /workspace
