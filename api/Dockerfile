FROM node:12

WORKDIR /raices/api

COPY package*.json ./

RUN npm install

COPY . ./

EXPOSE 9060

CMD ["npm", "start"]
