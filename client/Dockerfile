FROM node:alpine

COPY . /app
WORKDIR /app

RUN yarn install
RUN yarn run build

EXPOSE 3000

ENTRYPOINT ["/usr/local/bin/yarn", "run", "start"]
