##Curl requests
- curl -X POST "http://localhost:8081/shop" -H "accept: */*" -H "Content-Type: application/json" -d "{ \"address\": \"No. 2 Old, Mutare Rd, Harare\", \"area_id\": 1, \"shopname\": \"ECONET MASASA\"}"
- curl -X GET "http://localhost:8081/shop/area/1" -H "accept: */*"
