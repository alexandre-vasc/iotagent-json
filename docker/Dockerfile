FROM node:8

COPY . /opt/iotagent-json/
WORKDIR /opt/iotagent-json

RUN npm install && npm run-script build

ENTRYPOINT npm start ./config.json
