# HelloWorld
Simple Java webapp for Tomcat

# CI/CD & was test
# for maven
mvn clean package  --> target/HelloWorld.war

cp  target/HelloWorld.war  <WAS_WEBAPP_DIR>   --> automatically extract

# for gradle
gradle build --> build/libs/HelloWorld-1.0-SNAPSHOT.war

cp  build/libs/HelloWorld-1.0-SNAPSHOT.war  <WAS_WEBAPP_DIR>   --> automatically extract


# for test
 curl localhost:8080/HelloWorld/
