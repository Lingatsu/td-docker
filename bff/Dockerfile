FROM mdsol/java21-jdk

WORKDIR /app

# Copy all files inside target directory into /app directory
COPY ./target/* /app/

CMD [ "java","-jar","/app/bff-0.0.1-SNAPSHOT.jar"]