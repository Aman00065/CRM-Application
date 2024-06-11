This project is Mini CRM Application  
Our Mini CRM Application is designed to manage customer relationships and streamline business operations through efficient data management and analysis. This application includes a robust set of features to handle data ingestion, ensuring seamless integration and scalability.

Features:

Data Ingestion:
API Creation:
We have developed APIs to ingest data into the customer and orders databases. These APIs facilitate the entry of customer details and order information into the system, ensuring accurate and up-to-date records.
Postman Demonstration:
Using Postman, we demonstrate how these APIs are utilized to input data into the respective tables. This visual guide shows the process of hitting the APIs and confirms successful data ingestion.
Scalable Implementation:
For enhanced scalability, our implementation includes data validation at the API input level. This ensures that only valid data is accepted.
To handle high volumes of data efficiently, we employ a pub-sub model using a message broker. This model decouples the data ingestion process, allowing for asynchronous processing. The API performs the initial data validation, then publishes the data to a message broker. A consumer service subscribes to the message broker, retrieving and processing the data, and finally inserting it into the database.
This approach not only improves scalability but also ensures data integrity and consistency across the system.
Our Mini CRM Application offers a reliable and scalable solution for managing customer and order data, leveraging modern data ingestion techniques to enhance performance and user experience.







