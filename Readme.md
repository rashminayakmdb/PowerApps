# Title
MONGODB Data API Connector
The MongoDB Atlas Data API lets you read and write data in Atlas with standard HTTPS requests. The API includes endpoints that create, read, update, delete, and aggregate documents in your cluster.

## Publisher: Publisher's Name
MongoDB ​

## Prerequisites
You will need the following to proceed:

    MongoDB Atlas Account with a Cluster Running

## Supported Operations
Perform CRUD operayions and aggregations on your data in minutes

## Obtaining Credentials
For authentication, you need to use an API Key. To get a API key, follow the steps provided in the below section

## Pre-requisites for Using the Connector
1. Enable the Data API

        The Data API is disabled by default. To use the API, you need to turn it on in the Atlas UI for one or more clusters.
        Click Data API in the left navigation menu. On the following screen, select one or more clusters that you want to enable the API on from the dropdown menu and then click Enable the Data API.
2. Create a Data API Key

        The Data API uses project-level API keys to manage access and prevent unauthorized requests. Every request must include a valid Data API key.A Data API key grants full read and write access every collection in a cluster and can access any enabled cluster in the project.
        Click Create API Key, enter a unique name for the new key, and then click Create API Key.
        You can now see and copy your new API key for the first and only time. Once you close the modal, Atlas will never expose the value again.
