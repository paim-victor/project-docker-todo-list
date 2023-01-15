FROM node:14-alpine
EXPOSE 3001
WORKDIR /project
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "start" ]