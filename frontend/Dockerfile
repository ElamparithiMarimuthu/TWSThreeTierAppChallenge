FROM node:14

WORKDIR /app/frontend

COPY  package*.json /app/frontend

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "npm" , "start" ]
