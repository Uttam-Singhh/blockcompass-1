FROM node:10-alpine
WORKDIR /app/
ENV PATH /app/node_modules/.bin:$PATH
COPY package.json /app/package.json
RUN npm install
COPY . /app
EXPOSE 3001
CMD ["node", "server.js"]
