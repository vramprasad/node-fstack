FROM node:20.18-alpine
RUN apk add --no-cache tzdata
ENV TZ=Asia/Kolkata
WORKDIR /usr/src/app
COPY . .
RUN npm install
EXPOSE 5173