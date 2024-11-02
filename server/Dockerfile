FROM node:22.11.0-alpine3.20 AS prod
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8090
CMD ["npm", "run", "start"]