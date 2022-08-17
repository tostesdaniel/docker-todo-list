FROM node:14-alpine

WORKDIR /front-end

EXPOSE 3000

COPY . .

RUN npm install

ENTRYPOINT [ "npm", "start" ]