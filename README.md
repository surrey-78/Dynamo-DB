# EX-5-Overview-of-DynamoDB-in-AWS

## Aim
To understand and perform basic operations in Amazon DynamoDB, including table creation, item insertion, querying, and experimenting with simple data operations using the AWS SDK.

## Objectives
1.Set up an Amazon DynamoDB table.
2.Perform basic CRUD (Create, Read, Update, Delete) operations in DynamoDB.
3.Explore querying and scanning techniques.
4.Use the AWS SDK to interact with DynamoDB programmatically.

## Introduction
Amazon DynamoDB is a fully managed NoSQL database service provided by AWS. It's designed for high-performance applications requiring low-latency access to large volumes of data, making it ideal for use cases like web applications, IoT, and mobile backends. DynamoDB offers flexibility with its schema-less design and supports both key-value and document data structures.

## Required Tools
* AWS Account with DynamoDB access.
* AWS Management Console for web-based interactions.
* AWS SDK for Python (Boto3) for programmatic access.

## Instructions
## 1. Setting Up the Environment
* Log into the AWS Management Console.
* Navigate to DynamoDB under the Database section.

![first image](https://github.com/user-attachments/assets/47a8db33-e777-4ba5-93ee-9e914a1a6623)

## 2. Creating a Table in DynamoDB
* Go to Create Table.
* Enter a Table Name, such as ExperimentTable.
* Define the Partition Key (e.g., ItemID) and optionally a Sort Key (e.g., Timestamp).
* Configure Read/Write Capacity settings based on expected load.
* Click on Create Table to finalize.

<img width="1163" alt="second image" src="https://github.com/user-attachments/assets/c254c4ad-813a-44d3-b321-2bbf93e79b52">

## 3. Inserting Items
* Select the created table and go to the Items tab.
* Click on Create Item.
* Add attributes such as ItemID, Description, Status, etc.
* Click Save to store the item.

![third image](https://github.com/user-attachments/assets/b4589bbb-995e-42a1-b5d1-b1f3d6655ac1)

## 4. Querying Data
* Navigate to the Items tab of your table.
* Click Query to search by the primary key.
* Specify filters (e.g., by Status or Timestamp) for more refined results.

![fourth image](https://github.com/user-attachments/assets/78d81da0-ddb6-43a2-9c72-aab23dede527)

## 5. Experimenting with Advanced Features
Global Secondary Indexes (GSI): Set up GSIs for querying non-primary attributes. DynamoDB Streams: Enable streams to capture and process real-time changes. Auto Scaling: Configure read/write auto-scaling for dynamic workloads.

## RESULTS
Successfully create a DynamoDB table and manage data entries, Efficiently use DynamoDB’s querying and filtering options to retrieve data.
