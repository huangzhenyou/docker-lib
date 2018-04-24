FROM openjdk:8u131-jre-alpine
MAINTAINER <Huangzhenyou>

ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8
ENV TZ=Asia/Shanghai


RUN apk --update add wget bash tzdata \
    && cp /usr/share/zoneinfo/$TZ /etc/localtime \
    && echo $TZ > /etc/timezone
    
