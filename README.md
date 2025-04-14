# spring-boot-crud-example

wget http://localhost:8080/jnlpJars/jenkins-cli.jar

java -jar jenkins-cli.jar -s http://localhost:8080 install-plugin docker-plugin

java -jar jenkins-cli.jar -s http://localhost:8080 \
  -auth deepanshu:redhat \
  install-plugin docker-plugin



  curl -X POST http://product247.com/app/v1/addProduct -H "Content-Type: application/json" -d '{"id":1,"name":"Laptop","quantity":2,"price":80000}'


for v1.1.0

curl -X POST http://product247.com/app/v1.1/addProduct -H "Content-Type: application/json" -d '{
           "name": "laptop",
           "category": "electoronics",
           "price": 800000,
           "quantity": 10
         }'


curl -X GET "http://product247.com/app/v1.1/products/searchByCategoryAndPrice?category=electronics&minPrice=50000&maxPrice=900000"




