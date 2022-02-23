FROM node:14.15.1

WORKDIR /usr/src/app

COPY package*.json ./ 

RUN npm install --silent

COPY --chown=node:node . . 

USER  node

EXPOSE 3000 

CMD ["npm","start"]