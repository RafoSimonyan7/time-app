FROM node:alpine

WORKDIR /app/frontend

COPY frontend/package*.json ./

RUN npm i && npm cache clean --force

COPY ./frontend ./

EXPOSE 3000

CMD ["npm", "run", "dev"]
