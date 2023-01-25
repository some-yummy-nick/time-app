FROM node:alpine

WORKDIR /app

EXPOSE ${FRONTEND_PORT}

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm", "run" , "dev"]