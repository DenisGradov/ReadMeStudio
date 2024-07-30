FROM node:alpine

WORKDIR /app

EXPOSE 3030
COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]