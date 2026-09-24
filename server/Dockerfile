FROM node:20-alpine

WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy server source code
COPY . .

# Expose server port
EXPOSE 5000

# Start server
CMD ["npm", "start"]