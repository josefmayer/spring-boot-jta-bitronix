## JTA Bitronix Spring Boot
Bitronix Transaction Manager


### Technologies
JTA, Bitronix, Spring Boot <br />


### Model
Entity: <br />
Account <br />

AccountRepository <br />
JmsTemplate <br />

Service: Transactional <br />
Sends message to JmsTemplate <br />
Saves account in repository <br />


Transaction: <br />
Annotation: javax.transaction.Transactional <br />
Provider: Bitronix, defined in maven artifact <br />



### Steps
##### Build and Run Application
*mvn spring-boot:run* <br />

##### Run test
*mvn test* <br />


### Original Source:
https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples


