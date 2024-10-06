FROM node:20-alpine

RUN mkdir -p /usr/app
COPY . /usr/app/

WORKDIR /usr/app
EXPOSE 3080

RUN npm install
CMD ["node", "server.js"]