FROM node:alpine

WORKDIR /app

COPY ./frontend/package*.json ./frontend

RUN npm i && npm cache clean --force

COPY . ./

ENV BACKEND_URL=http://localhost:5555

CMD ["npm", "run", "dev"]
