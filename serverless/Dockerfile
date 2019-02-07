ARG NODE_VERSION=8.4.0
FROM node:${NODE_VERSION}
RUN npm config set unsafe-perm=true
RUN npm install -g serverless@1.37.0
ENTRYPOINT ["serverless"]
