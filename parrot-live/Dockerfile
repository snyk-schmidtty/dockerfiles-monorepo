FROM node:25.3.0-alpine3.23

RUN apk add --no-cache git
RUN git clone --branch master --depth 1 https://github.com/hugomd/parrot.live.git /src
WORKDIR /src
RUN npm install
CMD ["node","index.js"]
