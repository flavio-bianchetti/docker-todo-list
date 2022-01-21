FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /tests
ADD node_modules.tar.gz ./
COPY . .
RUN echo npm test