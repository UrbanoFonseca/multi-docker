FROM node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .

# This command will run the "start"
# command specified in the package.json
# file which is basically starting the 
# nodemon tool. 
CMD ["npm", "run", "start"]