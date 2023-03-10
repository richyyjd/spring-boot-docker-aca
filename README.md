# spring-boot-docker-aca
Deploy a spring boot app to ACA

### step 1
git clone git@github.com:richyyjd/spring-boot-docker-aca.git

### step 2
mvn clean compile package

### step 3, dockerize the app
docker build -t spring-boot-docker-aca .

### step 4, test the docker image
docker run -p 8080:8080 spring-boot-docker-aca -d

### step 5, open your web browser
http://localhost:8080/

### step 6, in progress...
