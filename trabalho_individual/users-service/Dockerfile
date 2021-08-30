FROM node:latest

WORKDIR /users-service
COPY package.json /users-service
RUN yarn
COPY . /users-service

EXPOSE 7101
CMD ["sh", "-c", "yarn db:migrate && yarn watch"]