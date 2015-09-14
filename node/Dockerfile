FROM node
MAINTAINER Micheal Waltz <ecliptik@gmail.com>

#Install node deps
WORKDIR /src
COPY . /src/
RUN npm install

# Expose port
EXPOSE  8080

# Run app using nodemon
ENTRYPOINT ["node", "/src/index.js"]
