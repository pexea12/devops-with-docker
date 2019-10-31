FROM node:alpine
LABEL maintainer="pexea12"

EXPOSE 5000
COPY calculator /calculator
WORKDIR /calculator
RUN ["npm", "install", "-g", "serve"]
CMD ["serve", "-s", "build"]

