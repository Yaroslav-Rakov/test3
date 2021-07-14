FROM node:14
# WORKDIR /usr/src/app
RUN mkdir /project
WORKDIR /project
# COPY package*.json ./
# RUN npm install

COPY . .

RUN npm install
EXPOSE 8000
CMD [ "node", "app.js" ]
