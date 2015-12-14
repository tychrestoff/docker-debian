FROM        tychrestoff/debian:jessie
MAINTAINER  tychrestoff

RUN cd tmp \
 && curl -SLO https://nodejs.org/dist/v4.2.3/node-v4.2.3-linux-x64.tar.gz \
 && tar -xzf node-v4.2.3-linux-x64.tar.gz -C /usr/local --strip-components=1 \
 && rm node-v4.2.3-linux-x64.tar.gz
