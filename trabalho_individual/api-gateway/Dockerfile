FROM node:latest

WORKDIR /api-gateway
COPY package.json /api-gateway
RUN yarn
COPY . /api-gateway

EXPOSE 7101
CMD ["yarn", "watch"]