FROM node:20-alpine

RUN apk update && apk add --no-cache git

WORKDIR /assignments

RUN git clone https://github.com/nueiwai/COMP-4964.git .

WORKDIR /assignments/Assignment2/backend

RUN npm install --production

EXPOSE 8080

CMD [ "npm", "start" ]
