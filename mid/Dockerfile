# Target: Use nestjs as base for MID API
# https://docs.nestjs.com/
FROM node:18-alpine

RUN npm i -g @nestjs/cli@10

WORKDIR /app

COPY package*.json .
RUN npm i

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
