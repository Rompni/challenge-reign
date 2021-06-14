FROM node:lts As development

WORKDIR /usr/src/app

COPY package.json /usr/src/app/package.json

RUN yarn install

COPY . /usr/src/app

EXPOSE 5000

CMD [ "yarn", "start:dev" ]
