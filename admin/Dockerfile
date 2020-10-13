FROM node:lts-alpine3.9

WORKDIR /admin

COPY package*.json /admin/
RUN npm install
COPY . /admin/

EXPOSE 3000
CMD ["npm", "start"]