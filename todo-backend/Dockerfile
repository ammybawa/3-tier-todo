from node:alpine
workdir /app
copy package*.json ./
run npm install
copy . .
EXPOSE 5000
cmd ["node","index.js"]
