FROM node:18.17.0-alpine
WORKDIR /app
COPY package.json ./
COPY package-lock.json ./
RUN npm i 
COPY . ./
EXPOSE 9999
CMD [ "npm", "start" ]