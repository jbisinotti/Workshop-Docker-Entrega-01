FROM node:latest

WORKDIR /chat-service
COPY package.json /chat-service
RUN yarn
COPY . /chat-service

EXPOSE 7100
CMD [ "yarn", "watch" ]