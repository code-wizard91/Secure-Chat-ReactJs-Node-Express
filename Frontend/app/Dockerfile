FROM node:alpine
WORKDIR /app
COPY package.json /app/package.json
ENV PATH /app/node_modules/.bin:$PATH
COPY . /app
RUN yarn install
CMD ["yarn", "start"]
