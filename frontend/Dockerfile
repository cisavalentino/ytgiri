FROM node:16-alpine

ENV VUE_APP_API_URL=http://localhost:8080

WORKDIR /app

COPY . .

RUN yarn install

CMD ["yarn","serve"]
