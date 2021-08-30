FROM node:latest

WORKDIR /usr/src/users
COPY package.json /usr/src/users
RUN yarn
COPY . /usr/src/users

EXPOSE 7101
CMD ["sh", "-c", "yarn db:migrate && yarn watch"]