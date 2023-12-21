FROM docker.io/alpine
RUN apk update && apk add nodejs
COPY ./ /src
WORKDIR /src
ENTRYPOINT ["node", "count-server.js"]