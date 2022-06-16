#base image
FROM node:14
#port export
EXPOSE 8080
#setting workdirectory
WORKDIR /opt/server
#copying package file
COPY package.json /opt/server/
#install the node dependencies
RUN npm install
#copy server file
COPY server.js /opt/server/
#run the application
CMD ["node", "server.js"]

