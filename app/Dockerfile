FROM node:16

WORKDIR /home/webpage

COPY ./index.js /home/webpage/index.js
COPY ./public /home/webpage/public
COPY ./package*.json /home/webpage/

RUN npm i
EXPOSE 8080
CMD ["npm", "run", "start"]