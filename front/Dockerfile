# Target: Use VUE as base for frontend
FROM node:18-alpine

WORKDIR /app

COPY package*.json .
RUN npm i

ENTRYPOINT [ "npm" ]
CMD [ "run", "dev", "--", "--host" ]
