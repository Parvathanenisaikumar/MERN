FROM node:18.9.1
LABEL frontend for application
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
CMD ["npm", "run", "dev"]
EXPOSE 5173

