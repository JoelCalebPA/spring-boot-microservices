FROM eclipse-temurin:17-jdk-alpine

ARG APP_JAR=${project.artifactId}-${project.version}.jar
ARG TEST=${test.name}

WORKDIR /app

COPY $APP_JAR .

ENTRYPOINT ["java", "-jar", "$APP_JAR"]