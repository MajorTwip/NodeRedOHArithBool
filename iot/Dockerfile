#
# Builds a custom docker image for node-red, openhab and some IoT services
#
FROM migoller/node-red-openhab

LABEL maintainer="MiGoller" \
      author="MiGoller" 

# Install additional "basic" nodes for openHAB
RUN npm install node-red-contrib-meraki-cmx
RUN npm install node-red-contrib-ifttt
