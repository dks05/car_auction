# Cars Auction Platform
### Introduction
The Cars Auction Platform is a comprehensive solution for conducting online car auctions. It allows dealers to participate in auctions, place bids, and purchase vehicles efficiently and transparently.

### Features
- On-demand auction initiation by the admin team.
- Real-time bidding process with a 24-minute auction duration.
- Auction extension by 2 minutes if bids are placed in the last 2 minutes.
- Notification system for dealers about auction events.
- Concurrency control for handling multiple bids simultaneously.

### Technologies
- Java with Spring Boot
- Spring Data JPA for database interactions
- PostgreSQL/MySQL as the database system (I used MySQL)
- Maven for dependency management

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Java JDK 17 or later
- Maven 3.6 or Gradle 6 (as per your build tool choice)
- An instance of PostgreSQL/MySQL running

### Installing

- Clone the repository to your local machine.
```
git clone https://github.com/dks05/car_auction.git
```
- Navigate to the project directory.
```
cd car_auction
```

- Build the project.
```
mvn clean install
```  
### Configuration
- Update the ```src/main/resources/application.properties``` file with your database connection details.

- <span style="color:red"><b>Add dummy data into auction table</b> </span>

### Running the application
- Run the Spring Boot application using your IDE or via the command line:

``` 
mvn spring-boot:run
```

- Click to [Open Swagger](http://localhost:8080/auction/swagger-ui/index.html)

