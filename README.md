<h2>RVBB#graphql-example APIs</h2>
<br>created date: Oct 15, 2020, by RVBB | B2B team

********************************************************************************************************* 
# Technology
	> Spring - GraphQl
	> MongoDB
	> MySQL
	> Spring AOP
	> Spring Data with 
	> Swagger 2	

### Features
	* Customer Management

### Integration
	* Auth-Services
	* Payment
	* CCC
	* Logistis	

### Docker build
	docker build -t b2b/graphql-example:1.0 .
	docker tag b2b/customer-service:1.0 apphub.rvbb.vn/b2b/graphql-example:1.0
	docker push apphub.rvbb.vn/b2b2/graphql-example:1.0

### Configuration & data
	+ [configuration] use K8s ConfigMap

### Unit Test
	gradlew build -x test to ignore unit tests
	gradlew bootRun  --> run application
	test one or many Class :   
	gradlew test --tests full_package_and_ClassName
	gradlew build test --tests *ClassName --> to test one or some classes  
	Import GraphQL.postman_collection.json file to Postman to test as client

### Reference Docs
    https://github.com/graphql-java-kickstart/graphql-spring-boot/blob/master/README.md