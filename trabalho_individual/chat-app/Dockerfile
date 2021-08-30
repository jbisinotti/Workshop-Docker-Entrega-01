FROM node:latest

WORKDIR /usr/src/chata
COPY package.json /usr/src/chata
RUN yarn
COPY . /usr/src/chata

EXPOSE 7001
CMD ["yarn", "watch"]