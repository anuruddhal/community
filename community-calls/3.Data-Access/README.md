# Community Call #3 - Data Access in Ballerina

- YouTube: https://www.youtube.com/watch?v=lLqvaLtC3m0
- Date: November 10, 2020
- Next community call: December 8, 2020
- Invite: https://wso2.zoom.us/j/97351774553?pwd=eGtaNjB3M3QvN1JXL0RXa3FwMVZZZz09

## Agenda

- Data Access in Ballerina
  - RDBMS Data Access and Manipulation
  - Batch execution and Stored Procedures
  - Transaction Handling
  - Data Access Best Practices
- Open discussion

## Slide Deck

https://www.slideshare.net/BallerinaLang/ballerina-community-call-data-access-in-ballerina

## Running the Samples

### Prerequisite

- Setup the DEMO Database by importing the `DEMO.sql` found in `./Implementation/resources/`.
- Add `mysql-connector-java-8.0.22.jar` from [here](https://dev.mysql.com/downloads/connector/j/) to `./Implementation/resources/`.
- Update Database connector configurations (JDBC Url, Username & Password) if different.

### Running the samples

- Use the following commands for specific scenarios
  - Querying `ballerina run query 5`
  - Data Manipulation   `ballerina run manipulation`
  - Batch Execute   `ballerina run batch_execute`
  - Stored Procedures   `ballerina run stored_procedures`
  - Transactions    `ballerina run transactions`

## References

- https://ballerina.io/swan-lake/learn/api-docs/ballerina/sql/
- https://ballerina.io/swan-lake/learn/api-docs/ballerina/java.jdbc/
- https://ballerina.io/swan-lake/learn/by-example/
