#GENERAR LA IMAGEN
<<<<<<< HEAD
# docker build -t app-authors .
=======
# docker build -t app-books .
>>>>>>> f24341fccb7de55565368a4e7186486a94704497

FROM eclipse-temurin:17.0.11_9-jre-jammy

RUN mkdir /app
WORKDIR /app

COPY build/quarkus-app/app ./app
COPY build/quarkus-app/lib/ ./lib
COPY build/quarkus-app/quarkus/ ./quarkus
COPY build/quarkus-app/quarkus-run.jar app.jar

CMD ["java","-jar","app.jar"]