# образ с установленной Java
FROM openjdk:17-ea-jdk-slim
WORKDIR /java
COPY docker.java .
# компилируем исходный файл
RUN javac docker.java
CMD [ "java", "docker" ]