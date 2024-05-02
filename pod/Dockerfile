# Use the official Node.js 14 LTS image as a parent image
FROM node:14

# Set the working directory to /app
WORKDIR /app

# Copy the file from your host to your current location
COPY . .

# Make port 3000 available to the world outside this container
EXPOSE 3000

# Run the app when the container launches
CMD ["node", "main.js"]
