# docker build --build-arg http_proxy=http://proxy.houston.hpecorp.net:8080 -t chavezom/px-dev:0.0.1 .
# docker push chavezom/px-dev:0.0.1
#
FROM portworx/px-dev

COPY ./consul/config.json /etc/pwx/config.json
