FROM node:alpine

WORKDIR '/app'
COPY package*.json yarn* ./
RUN yarn
COPY ./ ./

CMD ["yarn", "start"]
