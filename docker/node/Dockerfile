FROM node:19.6-slim
ENV LANG=C.UTF-8 \
    TZ=Asia/Tokyo
WORKDIR /app
COPY src/package.json src/yarn.lock ./
RUN yarn install
