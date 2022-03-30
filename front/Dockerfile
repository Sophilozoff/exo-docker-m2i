FROM node:12.14 as build
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 4200
CMD ["npm", "start"]

