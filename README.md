# gradle-web-eclipse

A small sample web application.

## Technologies
* Java 8
* Gradle 4.10.2
* JSF 2.2
* Weld 3.0.5
* Tomcat 8.0.53

## Usage
* Run ```./gradlew```
* Wait for a war file being assembled and deployed to an embedded Tomcat.
* Open ```http://localhost:8081/gradlewebeclipse/index.xhtml``` in a browser.
* Enter something into the input field and press the button. You should get the current time and your name as a response.
