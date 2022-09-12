FROM node:14

EXPOSE 3001

ADD node_modules.tar.gz .

WORKDIR /back-end/

COPY . .

ENTRYPOINT [ "npm", "start" ]

