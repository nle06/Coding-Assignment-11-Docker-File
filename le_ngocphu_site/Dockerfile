# Use an official node image as the base for building the React app
FROM node:14

# Set working directory
WORKDIR /le_ngocphu_site

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port the app runs on
EXPOSE 3000

# Start the React app
CMD ["npm", "start"]
