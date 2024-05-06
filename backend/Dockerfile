FROM node:21
WORKDIR /app
COPY . .
RUN npm i
COPY .env.sample .env
CMD ["npm","start"]
EXPOSE 5000
