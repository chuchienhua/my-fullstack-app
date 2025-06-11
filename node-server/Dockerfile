# FROM node:18
# WORKDIR /app
# COPY . .
# RUN npm install
# EXPOSE 3000
# CMD ["npm", "start"]

FROM node:18

WORKDIR /app

COPY package*.json ./
COPY node_modules ./node_modules
COPY . .

EXPOSE 3000
CMD ["npm", "start"]
