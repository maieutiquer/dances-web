FROM node:22-slim

WORKDIR /usr/app

COPY package*.json ./
RUN npm install --legacy-peer-deps -qy

COPY . .

EXPOSE 5173

CMD ["npm", "start"]
