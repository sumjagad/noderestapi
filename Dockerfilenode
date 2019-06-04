FROM node
RUN npm install -y --verbose express --save
RUN npm install -y body-parser --save
COPY data.json /node/data.json
COPY node.js /node/node.js
RUN chmod +x /node/node.js
EXPOSE 9000
CMD node /node/node.js
LABEL MAINTAINER sumj@orcl.com
