# GWT Web Application Starter Project

Official gwt sample but with maven :b 

# Requirements

- java 8
- maven

# Build and Deploy

```
mvn clean package && mvn tomcat7:run-war-only
```

This will build and deploy using a temporary tomcat with base context /

If no erros, open your browser pointing at:

```
http://localhost:8082/
```

You must see this home:

![https://i.ibb.co/LvJzzZX/gwt-2-9-0-home.png](https://i.ibb.co/LvJzzZX/gwt-2-9-0-home.png)

And if you press send button:

![https://i.ibb.co/cht21qL/gwt-2-9-0-response.png](https://i.ibb.co/cht21qL/gwt-2-9-0-response.png)

# Just build


```
mvn clean package
```

This will create a war **hello-world-gwt-1.0.0.war** inside target folder. Copy and paste this war into tomcat/webapps and if no erros, open your browser pointing at:

```
http://localhost:8080/hello-world-gwt-1.0.0/
```

# References

- https://www.twilio.com/blog/2017/01/install-java-8-apache-maven-google-web-toolkit-windows-10.html
- http://www.gwtproject.org/download.html
- https://github.com/steinsag/gwt-maven-example
