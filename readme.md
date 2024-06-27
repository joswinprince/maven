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

## Running xml along with application.properties

mvn -f D:\Archimedis\test-automation\pom.xml test -Dtestng.xml.file=testng.xml -Dapplication.properties.file=D:\working\application.properties
