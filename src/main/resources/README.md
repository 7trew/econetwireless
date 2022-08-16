#Econet Wireless Coding exercise

##Curl requests
- curl -X POST "http://localhost:8081/shop" -H "accept: */*" -H "Content-Type: application/json" -d "{ \"address\": \"No. 2 Old, Mutare Rd, Harare\", \"area_id\": 1, \"shopname\": \"ECONET MASASA\"}"
- curl -X GET "http://localhost:8081/shop/area/1" -H "accept: */*"

##Deployment
- make sure you have java 1.8 installed on the deployment server
- compile the code using `$ mvn clean install`
- run the compiled jar using `$ java -jar econetwireless-0.0.1-SNAPSHOT.jar`
- consumer the API using the port number `8081`
- incase of errors visit `http://localhost:8081/swagger-ui.html`

##Video URL
[https://drive.google.com/file/d/1UWptcETCh0dpiKwzVLWQPOi63i1h-6ZI/view?usp=sharing](https://drive.google.com/file/d/1UWptcETCh0dpiKwzVLWQPOi63i1h-6ZI/view?usp=sharing)