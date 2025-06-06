FROM node:22.16-bullseye-slim

LABEL maintainer="solxyz"

WORKDIR /app

RUN apt-get update && apt-get install -y git

COPY package.json package-lock.json ./

## Install textlint configures
RUN npm ci

COPY . .
