FROM node:16

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build:docker

EXPOSE 8080

CMD [ "node", "dist/app.js" ]