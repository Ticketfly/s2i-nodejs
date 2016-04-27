FROM ryanj/centos7-s2i-nodejs:6.0.0

# Install app dependencies
USER root

RUN npm install -g ember-cli bower

USER 1001

EXPOSE 4200
