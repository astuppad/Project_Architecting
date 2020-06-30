# specify base image
FROM node:alpine

# set the working directory
WORKDIR /ur/app

# Install som dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Run the command
CMD ["npm", "start"]
