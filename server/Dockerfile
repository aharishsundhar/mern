# FROM node:14.11.0-alpine
# WORKDIR /mernapp
# COPY . .
# RUN npm install
# EXPOSE 5000
# CMD ["npm", "run", "dev"]
FROM node:14.11.0-alpine
WORKDIR /mernapp
COPY . .
RUN npm install
EXPOSE 5000
CMD [ "npm", "start" ]