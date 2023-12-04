FROM node:14

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install application dependencies
RUN npm install

# Copy the application code to the working directory
COPY . .

# Expose the port your app will run on inside the container
EXPOSE 3000

# Define the command to run your application
CMD ["node", "app1.js"]

