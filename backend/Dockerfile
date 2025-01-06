FROM node
EXPOSE 8080
RUN mkdir /opt/server
WORKDIR /opt/server
COPY *.js .
COPY *.json .
RUN npm install
CMD ["node","index.js"]
