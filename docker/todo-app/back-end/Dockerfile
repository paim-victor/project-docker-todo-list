FROM node:14

EXPOSE 3001

ADD node_modules.tar.gz .

WORKDIR /project

COPY . .

CMD [ "npm", "start" ]