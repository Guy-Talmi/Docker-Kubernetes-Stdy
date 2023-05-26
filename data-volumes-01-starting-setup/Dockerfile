FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ARG DEFAULT_PORT=80

# ENV PORT 80
ENV PORT $DEFAULT_PORT

EXPOSE $PORT

#EXPOSE 80

# VOLUME ["/app/feedback"]

# CMD ["node", "server.js"]
CMD ["npm", "start"]