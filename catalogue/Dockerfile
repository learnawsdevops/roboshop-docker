FROM node:20
ENV MONGO=true
WORKDIR /app
COPY package.json /app/
RUN npm install
COPY *.js /app/
CMD ["node", "server.js"]
