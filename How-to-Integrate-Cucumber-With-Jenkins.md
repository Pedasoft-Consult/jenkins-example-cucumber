Gist for https://www.youtube.com/watch?v=T5BHpvC5PL8

# Steps from the video

* `gh repo create jenkins-example-cucumber --gitignore Maven --public --clone`
* `mvn archetype:generate -DgroupId=com.planetpope.cucumber -DartifactId=jenkins-example-cucumber -DarchetypeGroupId=io.cucumber -DarchetypeArtifactId=cucumber-archetype -DarchetypeVersion=7.2.3 -DinteractiveMode=false`
* `cd jenkins-example-cucumber`
* `mvn -N io.takari:maven:wrapper -Dmaven=3.8.4`
* `./mvnw clean test`
