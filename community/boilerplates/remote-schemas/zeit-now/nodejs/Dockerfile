FROM node:23.11.0-bookworm-slim

WORKDIR /server

COPY ./package.json /server/

RUN npm install

COPY . /server/

CMD ["npm", "start"]
