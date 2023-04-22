FROM node:alpine

WORKDIR /app

COPY api/package*.json ./

RUN npm i && npm cache clean --force

COPY . ./

CMD ["npm", "run", "dev"]
