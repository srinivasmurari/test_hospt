FROM alpine:latest
# Update the package repository and install curl
RUN apk update && \
    apk add --no-cache curl && \
    apk upgrade
RUN mkdir /opt/liferay
RUN mkdir /opt/liferay/deploy
ADD modules/build  /opt/liferay/deploy
