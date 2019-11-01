FROM ubuntu:16.04
RUN apt-get update && apt-get install curl -y
CMD echo "Input website:"; read website; echo "Searching.."; sleep 1; curl -L http://$website;
