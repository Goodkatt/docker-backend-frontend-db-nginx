FROM node

RUN mkdir /app

WORKDIR /app

COPY . .

RUN npm install

#COPY . .

EXPOSE 3000

CMD ["npm", "start"]
