FROM node:14
WORKDIR /app
COPY package*.json./
RUN npm install
COPY . .
EXPOSE 3002
CMD ["node","index.js"]

# docker buid -t user-service:latest ./user-service
# docker buid -t product-service:latest ./product-service

# docker run-d -p 3001 user-service
# docker run-d -p 3001 product-service