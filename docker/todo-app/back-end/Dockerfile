FROM node:14-alpine

WORKDIR /back-end

EXPOSE 3001

COPY . .

RUN npm install

ENTRYPOINT [ "npm", "start" ]