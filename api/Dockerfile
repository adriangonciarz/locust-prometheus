FROM node:latest

WORKDIR /mnt/api

RUN npm install -g json-server

CMD json-server --watch /mnt/api/db.json --port 3333 --host 0.0.0.0