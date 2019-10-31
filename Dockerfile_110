FROM node:alpine

COPY frontend-example-docker /frontend-example-docker
WORKDIR /frontend-example-docker
EXPOSE 5000
RUN ["npm", "install"]
CMD ["npm", "start"]

