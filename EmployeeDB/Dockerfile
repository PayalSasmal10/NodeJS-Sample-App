FROM node:16

WORKDIR /usr/src/app

COPY package.json /usr/src/app

Run npm install

COPY . .

EXPOSE  3000

CMD [ "node", "app.js" ]

