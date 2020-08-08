FROM alpine
LABEL maintainer="umarhassanmalik15@gmail.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Umar Hassan Malik"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]
