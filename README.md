# Reqirements
* Java 8
* Maven - You can install Maven by following this [link](https://github.com/Dcbaas/opengl-java-project-maven/wiki/Installing-Maven)


# How to use. 
1. Make sure main method is configured correctly in pom.xml
2. Run Maven package for specified operating system
* Window: Type ```mvn package -Plwjgl-natives-windows-amd64```
* Mac: Type ```mvn package -Plwjgl-natives-macos-amd64```
* Linux: Type ```mvn package -Plwjgl-natives-linux-aarch64```

3. Run the program from terminal by typing ```java -jar .\target\mygame-1.0-SNAPSHOT-jar-with-dependencies.jar```
