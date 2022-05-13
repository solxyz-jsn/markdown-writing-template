FROM node:16.15-bullseye-slim

LABEL maintainer="hikaruright"

RUN apt-get update && apt-get install -y git

## Install textlint configures
RUN npm install -g textlint \
    textlint-filter-rule-comments \
    textlint-filter-rule-node-types \
    textlint-filter-rule-whitelist \
    textlint-plugin-review \
    textlint-rule-max-ten \
    textlint-rule-no-mix-dearu-desumasu \
    git+https://github.com/ics-creative/textlint-rule-preset-icsmedia.git \
    textlint-rule-preset-japanese \
    textlint-rule-preset-jtf-style \
    textlint-rule-prh \
    textlint-rule-report-node-types

