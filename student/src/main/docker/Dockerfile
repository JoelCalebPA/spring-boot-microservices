FROM eclipse-temurin:17-jdk-alpine

ARG JAR=${project.artifactId}-${project.parent.version}.jar

WORKDIR /app

EXPOSE 8090

COPY $JAR .

ENTRYPOINT ["java", "-jar", "$JAR"]