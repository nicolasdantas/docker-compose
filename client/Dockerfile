FROM node:current-alpine3.10

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json ./
COPY public public
COPY src src


RUN npm install

CMD ["npm", "start"]