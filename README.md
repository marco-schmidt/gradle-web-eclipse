# gradle-web-eclipse

A small sample web application.

## Technologies
* Java 8
* Gradle 4.6
* JSF 2.2
* Weld 3.0.3
* Tomcat 8.0.50

## Usage
* Run ```./gradlew```
* Wait for a war file being assembled and deployed to an embedded Tomcat.
* Open ```http://localhost:8080/gradlewebeclipse/index.xhtml``` in a browser.
* Enter something into the input field and press the button. You should get the current time and your name as a response.
