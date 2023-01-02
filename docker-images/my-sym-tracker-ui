FROM debian:bullseye-slim
RUN mkdir /app
WORKDIR /app
# Install NodeJS
RUN apt update
RUN apt install wget -y
RUN wget https://deb.nodesource.com/setup_18.x -O ./node.js
RUN bash ./node.js
RUN apt update
RUN apt install nodejs -y
# Install App
RUN apt install git -y