FROM node:alpine

WORKDIR /app/api

COPY api/package*.json ./

RUN npm i && npm cache clean --force

COPY ./api ./

EXPOSE 5000

CMD ["npm", "run", "dev"]
