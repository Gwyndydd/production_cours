#Tag mobile qui peut accèder aux mise à jour de java 21
FROM eclipse-temurin:21-jre-alpine

#Création du repertoire dédiée
WORKDIR /app

COPY target/backend-*.jar app.jar

EXPOSE 8080

CMD ["java","-jar","app.jar"]