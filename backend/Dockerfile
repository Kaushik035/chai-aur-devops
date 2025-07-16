FROM node:20 

WORKDIR /AppBackend

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8080

CMD ["npm", "start"]

