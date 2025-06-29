FROM node:alpine

WORKDIR /react-application

COPY /package*.json /react-application/

RUN npm install

COPY . /react-application

CMD ["npm","start"]