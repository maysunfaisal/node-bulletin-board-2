FROM node:current-slim

WORKDIR /usr/src/app
COPY . .

RUN pwd

RUN ls -la

RUN npm install

RUN echo 22

EXPOSE 3000
CMD [ "npm", "start" ]
