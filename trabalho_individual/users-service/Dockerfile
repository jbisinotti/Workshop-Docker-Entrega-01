FROM node:latest

WORKDIR /user-service
COPY package.json /user-service
RUN yarn
COPY . /user-service

EXPOSE 7101
CMD ["sh", "-c", "yarn db:migrate && yarn watch"]