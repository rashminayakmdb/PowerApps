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
For authentication, you need to use an API token. To get a token, follow the steps in ## Pre-requisites for Using the Connector

## Pre-requisites for Using the Connector
1. Enable the Data API
        The Data API is disabled by default. To use the API, you need to turn it on in the Atlas UI for one or more clusters.
        Click Data API in the left navigation menu. On the following screen, select one or more clusters that you want to enable the API on from the dropdown menu and then click Enable the Data API.
2. Create a Data API Key
        The Data API uses project-level API keys to manage access and prevent unauthorized requests. Every request must include a valid Data API key.A Data API key grants full read and write access every collection in a cluster and can access any enabled cluster in the project.

        Click Create API Key, enter a unique name for the new key, and then click Create API Key.
        You can now see and copy your new API key for the first and only time. Once you close the modal, Atlas will never expose the value again.
3. Send a Data API Request
        You include your Data API key when you call action endpoints that read and write documents in MongoDB. 

## Using the Connector

1. Make sure you've followed the pre-requisites.
2. To use this connector, go to Power Automate and click Data on the left navigation page. Then, click Custom connectors.
3. Wait for the page to load. Then, click +New custom connector.
4. From the dropdown, select Import from GitHub. For Connector Type, choose Custom. For Branch, choose dev. For Connector, choose MongoDB DataApi.
5. Click Continue. You will now be taken the the Custom Connector UI, which will populate the connector files, including the code file, into the UI.
6. In Step 1: General, make sure to replace the "YourInstance" in the Host URL field with your own instance. You can learn more about this field here.


## Known Issues and Limitations
Required. Include any known issues and limitations a user may encounter.

## Deployment Instructions
Required. Add instructions on how to deploy this connector as custom connector.