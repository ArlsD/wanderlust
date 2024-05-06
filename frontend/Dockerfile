FROM node:21
WORKDIR /app
COPY . .
RUN npm i
COPY .env.sample .env.local
CMD ["npm","run","dev","--","--host"]
EXPOSE 5173
