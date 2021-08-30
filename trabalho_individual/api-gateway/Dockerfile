FROM node:latest

WORKDIR /usr/src/users
COPY package.json /usr/src/users
RUN yarn
RUN yarn db:migrate
COPY . /usr/src/users

EXPOSE 7101
CMD ["yarn", "watch"]