FROM node:latest

WORKDIR /chat-app
COPY package.json /chat-app
RUN yarn
COPY . /chat-app

EXPOSE 7001
CMD ["yarn", "watch"]