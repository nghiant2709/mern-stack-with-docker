FROM node:14
WORKDIR /frontend
COPY package*.json .
RUN npm install
COPY . . 
EXPOSE 7002
CMD ["npm", "start"]