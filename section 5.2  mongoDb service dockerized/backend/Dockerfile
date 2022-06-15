FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

ENV MONGODB_USERNAME=pkindalov
ENV MONGODB_PASSWORD=secret

CMD [ "npm", "start" ]