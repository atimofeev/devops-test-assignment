FROM nginx:1.25.3

RUN apt-get update && \
    apt-get install -y nodejs=18.13.0+dfsg1-1

WORKDIR /usr/src/app

COPY package*.json index.js ./

EXPOSE 3000

CMD ["node", "index.js"]
