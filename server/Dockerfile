FROM node:22-slim

WORKDIR /usr/app

COPY package*.json ./
RUN npm install -qy

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
