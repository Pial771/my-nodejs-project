# Use an official Node.js image from the Docker Hub
FROM node:20

# Create and set the working directory
WORKDIR /app

# Copy package.json and package-lock.json files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port the app runs on
EXPOSE 3010

# Start the app
CMD ["node", "index.js"]
