FROM node:18-alpine
WORKDIR /app
COPY . .
RUN npm install --omitdev
EXPOSE 3000
CMD ["node", "index.js"]
