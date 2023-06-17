#
# Builds a custom docker image for node-red and openhab
#
FROM nodered/node-red

LABEL maintainer="MajorTwip" \
      author="MajorTwip" 

# Install additional "basic" nodes for openHAB
RUN npm install node-red-contrib-bigtimer
RUN npm install node-red-contrib-openhab3
RUN npm install node-red-contrib-boolean-logic-ultimate
RUN npm install node-red-contrib-calc
RUN npm install @binsoul/node-red-contrib-deye-sun-g3
RUN npm install node-red-contrib-buffer-parser

# Define volume for Node-RED userdata: Settings, flows, ...
VOLUME ["/data"]
