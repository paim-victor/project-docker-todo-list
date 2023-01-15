FROM node:14

EXPOSE 3001

ADD node_modules.tar.gz .

WORKDIR /home/paim/projetos-back-end/sd-025-a-project-docker-todo-list

COPY . .

CMD [ "npm", "start" ]