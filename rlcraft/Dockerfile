FROM openjdk:8-alpine
ARG SERVER_SRC_DIR=./temp-src
WORKDIR /server
COPY $SERVER_SRC_DIR /server
EXPOSE 25565
CMD java -Xmx4096M -Xms4096M -jar forge-server.jar nogui

