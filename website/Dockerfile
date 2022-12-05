FROM node:16

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

EXPOSE 8080

CMD [ "npx", "http-server", "-p" ,"8080", "www/" ]