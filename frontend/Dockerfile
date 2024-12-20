FROM node:20

WORKDIR /app

COPY package.json .

#RUN npm config set registry http://registry.npmjs.org/
RUN npm install

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]
