# 111


Step 1: Setting Up Git Repository

git init
Step 2: Creating and Committing Changes

git status
git add example.txt
git commit -m "Add content to example.txt"
Step 3: Exploring History

git status
git diff
git log
Step 4: Branching and Merging

git branch feature
git checkout -b feature (shorthand for creating and switching to a new branch)
git commit -m "Commit message for feature branch"
git checkout master
git merge feature
Step 5: Collaborating with Remote Repositories

git remote add origin <repository_url>
git push origin master


# Use an official Apache image as the base imageFROM
httpd:2.4
# Copy your custom HTML page to the web server's document rootCOPY
index.html /usr/local/apache2/htdocs/

docker build -t my-apache-server .
docker run -p 8080:80 -d my-apache-server

for maven 

pom.xml

<project xmlns="http://maven.apache.org/POM/4.0.0"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
http://maven.apache.org/xsd/maven-4.0.0.xsd">
<modelVersion>4.0.0</modelVersion>
<groupId>com.example</groupId>
<artifactId>MavenDemo</artifactId>
<version>1.0-SNAPSHOT</version>
</project>

<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0
                             http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    <groupId>com.example</groupId>
    <artifactId>MavenDemo</artifactId>
    <version>1.0-SNAPSHOT</version>
</project>

mvn clean compile test package install deploy

java -cp target/MavenDemo-1.0-SNAPSHOT.jar HelloWorld



