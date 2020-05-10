FROM node:13.12.0
WORKDIR /app
COPY . /app
RUN yarn install && yarn build && npm install -g http-server
EXPOSE 3000
CMD http-server ./build -p 3000