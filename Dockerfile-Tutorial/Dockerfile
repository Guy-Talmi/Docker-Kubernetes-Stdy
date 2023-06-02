FROM node:13-alpine

ENV MONGO_DB_USERNAME=admin
ENV MONGO_DB_PWD=password

# linux command
RUN mkdir -p /home/app

# execute on the host
COPY . /home/app

# entry point linux command
CMD [ "node", "/home/app/server.js" ]
