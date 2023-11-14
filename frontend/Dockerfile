FROM node:alpine

WORKDIR /app

COPY package* .

RUN npm install

COPY . .

EXPOSE 3333

CMD ["npm", "run", "dev"]

