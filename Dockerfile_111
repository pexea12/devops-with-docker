FROM node:alpine

COPY backend-example-docker /backend-example-docker
WORKDIR /backend-example-docker
EXPOSE 8000
RUN ["npm", "install"]
CMD ["npm", "start"]

