FROM mjgargani/puppeteer:trybe1.0 AS todotests

ADD node_modules.tar.gz .

WORKDIR /tests/

COPY . .

ENTRYPOINT [ "npm", "test"]
