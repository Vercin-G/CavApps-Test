# Use an official Node.js runtime as the base image
FROM node:lts-alpine

COPY . /src
# Install the dependencies
WORKDIR /src

RUN npm install

# Expose the port that the HTTP server will use
EXPOSE 3000

# Set the command to run the HTTP server when the container starts
CMD [ "npm","run","dev" ]
