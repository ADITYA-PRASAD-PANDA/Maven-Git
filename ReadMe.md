
# Create Maven-Web Application
. mvn archetype:generate -DarchetypeArtifactId=maven-archetype-webapp -DgroupId=in.aditya -DartifactId=maven-web-app -DinteractiveMode=false

# Add Spring-core dependency in pom.xml
. https://mvnrepository.com/artifact/org.springframework/spring-core/6.1.10(copy the dependency in pom.xml)

# Package maven project as war file using maven goal
### cd foldername/
### mvn clean compile
### mvn test
### mvn package

# Push maven project into github repo using gitbash(target folder shouldn't be commited , add this is .gitignore file)
### gitignore -> target/
