# Base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy files
COPY package*.json ./
RUN npm install

COPY . .

# Expose port and run
EXPOSE 3202
CMD ["node", "server.js"]

