FROM kkarczmarczyk/node-yarn:6.9

MAINTAINER Christian Dornbusch <christian.dornbusch@useeds.de>

# Global install grunt
RUN npm install --global grunt-cli

# Install Ruby.
RUN \
  apt-get update && \
  apt-get install -y ruby ruby-dev ruby-bundler && \
  rm -rf /var/lib/apt/lists/*

# Install Compass.
RUN gem install compass
    # apt-get install -y ruby ruby-compass && \
    # apt-get build-dep -y --force-yes ruby-compass && \
    # gem install compass

WORKDIR /workspace