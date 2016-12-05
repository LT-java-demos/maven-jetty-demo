#maven-jetty-demo

###maven-jetty-plugin:
[https://www.eclipse.org/jetty/documentation/9.3.x/jetty-maven-plugin.html](https://www.eclipse.org/jetty/documentation/9.3.x/jetty-maven-plugin.html)
 
 

###pom.xml
```xml
<build>
    <plugins>
        <plugin>
            <groupId>org.eclipse.jetty</groupId>
            <artifactId>jetty-maven-plugin</artifactId>
            <version>9.3.14.v20161028</version>
        </plugin>
    </plugins>
</build>
```
 
###Run
```shell
$ mvn jetty:run
```


[http://localhost:8080](http://localhost:8080) , you will see `Hello World!`
