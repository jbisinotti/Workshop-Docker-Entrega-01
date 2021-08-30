FROM node:latest

WORKDIR /usr/src/chats
COPY package.json /usr/src/chats/
RUN yarn
COPY . /usr/src/chats

EXPOSE 7100
CMD [ "yarn", "watch" ]