FROM node:24-alpine

WORKDIR /app

COPY package.json /app/

RUN npm install

COPY . /app

EXPOSE 80

CMD ["npm", "start"]