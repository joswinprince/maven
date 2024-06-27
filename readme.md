## Maven
### Create a Proect
```
mvn archetype:generate -DgroupId=com.example -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```
## Compiling
```
mvn -f D:\..\..\pom.xml compile
```
## Packaging
```
mvn -f D:\..\..\pom.xml package
```
## Packaging 
mvn test -f /full/path/to/your/project/pom.xml -Dtestng.xml.file=/path/to/your/testng.xml
