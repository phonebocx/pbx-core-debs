FROM basedocker

RUN apt-get -y install xmlstarlet flite1-dev flite
RUN mkdir -p /usr/local/build

COPY *deb /usr/local/build

RUN apt -y install /usr/local/build/*deb
