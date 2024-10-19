FROM node

WORKDIR /onedrive/desktop/aayu_devops/nodejs/node-bind-mount-project

COPY . .

RUN npm ci

ENV PORT=3000

CMD [ "npm", "start" ]