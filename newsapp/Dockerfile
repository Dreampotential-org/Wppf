# pull the official base image
FROM node:alpine
# set working direction
WORKDIR /app
# install application dependencies
COPY package.json ./
COPY . ./

# RUN npm i -g yarn
RUN npm i -g vite
RUN npm install


# PORTS
EXPOSE 5173

# start app
CMD ["npm", "run" ,"dev"]
