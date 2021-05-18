FROM node

WORKDIR /Users/lazylackof_a/Documents/HpOldH/docker-training/nodeserver

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080
CMD [ "npm", "start" ]
