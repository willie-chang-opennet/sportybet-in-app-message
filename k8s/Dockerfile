FROM 942878658013.dkr.ecr.eu-central-1.amazonaws.com/third-party/eclipse-temurin:21.0.2_13-jdk-jammy

ARG BUILD_NO
ENV APPLICATION_VERSION=$BUILD_NO

WORKDIR /root
ADD ./sportybet-in-app-message/target/sportybet-in-app-message.jar /app.jar
