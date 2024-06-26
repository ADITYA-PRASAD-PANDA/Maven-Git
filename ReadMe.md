
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
### git init
### git status
### git add . (It will staged the files)
### git status
### git commit -m "message" (the staged files will store in local repo)
### git push (the local repo will move to GitHub repo)


# Make changes in pom.xml and push changes to GitHub repo using git bash
### Version changed from 3.8.1 to 3.8.2
