# Specify a base image
FROM node:alpine

# Working directory in the container 
WORKDIR /usr/app

# copy package.json from current local directory to the current working directory of the container 
COPY ./package.json ./
# Install some dependencies
RUN npm install
# COPY (path to folder to copy from on *your machine*) (place to copy stuff to inside *the container*)
COPY ./ ./

# Default command 
CMD ["npm", "start"]