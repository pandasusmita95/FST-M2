# Specify Base Image
#podman build Specify Base Image
FROM docker.io/node:18-alpine

# Work Directory
WORKDIR /usr/app
#copy the package.json first
COPY ./package.json ./



# Install Dependencies
RUN npm install


# COPY Files
COPY ./ ./

# Startup Command
CMD ["npm", "start"]