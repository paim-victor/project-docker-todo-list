FROM mjgargani/puppeteer:trybe1.0
WORKDIR /project-test
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "test" ]