FROM mjgargani/puppeteer:trybe1.0

ADD node_modules.tar.gz .

WORKDIR /home/paim/projetos-back-end/sd-025-a-project-docker-todo-list

COPY . .

CMD [ "npm", "test" ]
