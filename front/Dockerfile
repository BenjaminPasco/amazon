FROM node:16-alpine

WORKDIR /

COPY /front/package.json .

RUN npm install

COPY ./front .

CMD ["npm", "start"]

EXPOSE 3000