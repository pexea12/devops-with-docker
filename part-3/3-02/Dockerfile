FROM python:alpine

RUN apk add --no-cache gcc libc-dev libxslt-dev libxml2-dev wget && \
      pip install yle-dl && \
      apk del gcc libc-dev
WORKDIR /app
ENTRYPOINT ["yle-dl"]
