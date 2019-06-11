FROM node:8

# Prepare app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app/
ADD . /usr/src/app/

RUN npm install --silent

# Start service
EXPOSE 3000
CMD [ "npm", "start" ]
