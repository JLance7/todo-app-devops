FROM node:16-alpine
WORKDIR /app
COPY package.json yarn.lock ./
RUN yarn install
COPY . .
ENV NODE_ENV dev
EXPOSE 3000
CMD ["npm", "start"]