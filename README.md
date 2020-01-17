from http://www.pretechsol.com/2014/12/java-ee-websocket-simple-example_12.html
https://blog.openshift.com/how-to-build-java-websocket-applications-using-the-jsr-356-api/
mvn package 
to create the war file
Copy the war file from target directory into the webapps directory of a tomcat server.
Run the tomcat server.
hit http://localhost:8080/pretech-websocket-example-1.0-SNAPSHOT/hello.html
For each message received, the server sends 10 messages back.