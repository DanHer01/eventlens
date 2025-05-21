# Use official Node.js LTS image as base
FROM node:18-alpine

# Set working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json if present
COPY package.json ./

# Install dependencies
RUN npm install --production

# Copy source code
COPY . .

# Expose port (change if your service uses a different port)
EXPOSE 3000

# Start the service
CMD ["npm", "start"]