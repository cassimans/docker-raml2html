FROM node:6.9.2-alpine

RUN npm install -qg raml2html@~3.0 \
 && npm cache clean

RUN mkdir -p /data
WORKDIR /data

CMD ["--help"]
