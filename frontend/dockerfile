FROM node:alpine

WORKDIR /11.10.23

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8954

CMD [ "npm", "run", "dev" ]