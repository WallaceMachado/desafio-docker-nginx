FROM node:15 As builder

WORKDIR /usr/src/app

COPY . .

RUN npm i

EXPOSE 3000

CMD [ "npm", "start" ]