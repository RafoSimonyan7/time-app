FROM node:alpine

WORKDIR /app

COPY api/package*.json ./

RUN npm i && npm cache clean --force

COPY ./api ./api

EXPOSE 5555

CMD ["npm", "run", "dev"]
