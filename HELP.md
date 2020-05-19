
pre-requisite 
install Docker 

checkout the code  https://github.com/ajithkumar9754/spring-boot.2.3.0-dockerization-without-DockerFile.git

Navigate to project folder

run command 
  mvn  spring-boot:build-image

 verify the image created for the application
  docker images

 Console Output should be like this <repository> and <tag>

  spring-boot.2.3.0-docker             0.0.1-SNAPSHOT      
