FROM node:8.1.2-alpine

LABEL Sean Bradley <seanwasere@gmail.com>

RUN mkdir -p /nodejs
COPY . /nodejs
WORKDIR /nodejs

RUN npm install -g babel-cli
RUN npm install

EXPOSE 8080:8080