FROM node:alpine

WORKDIR /server

COPY package.*json .


RUN npm install

COPY . .

RUN ls -al 

RUN npm run build

EXPOSE 5000

CMD [ "npm", "start" ]