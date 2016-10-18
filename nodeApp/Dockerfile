FROM node:argon

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /home/rick/Desktop/nodeApp

# Install app dependencies
COPY package.json /home/rick/Desktop/nodeApp
RUN npm install

# Bundle app source
COPY . /home/rick/Desktop/nodeApp

EXPOSE 8888
CMD [ "npm", "start" ]

