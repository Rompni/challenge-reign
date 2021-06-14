FROM node:lts

WORKDIR /usr/src/app

COPY package.json /usr/src/app

RUN yarn install

COPY . /usr/src/app 

RUN yarn build

EXPOSE 3000

CMD [ "yarn", "start" ]