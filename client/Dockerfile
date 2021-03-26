FROM node:14.11.0-alpine
WORKDIR /mernapp
COPY . .
RUN npm install react-scripts -g --silent
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]
