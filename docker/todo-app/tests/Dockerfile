FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests

COPY . .

RUN npm install

ENTRYPOINT [ "npm", "test" ]