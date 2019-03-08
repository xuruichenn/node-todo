FROM node:8

COPY package.json package.json
RUN npm install 

COPY server.js server.js
COPY app/ app/
COPY config/ config/
COPY public/ public/

CMD ["npm", "start"]
