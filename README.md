# 601-Project2-phase2

This is a NLP test trail. In this project, we try to use the google natural language API to analyize some entities.

# Preparation
## Deploy Google Cloud Platform (GCP)
First we need a account for GCP. We can easily get a google cloud platform account with our google account. Then you can create your first project on GCP.

## Create the first NLP test project
- In the management background interface, select or create a new project. Then you can see the generated project in the project list.

## Enable billing
- Allow bills for the project and set up an account. Click the drop-down menu on the left and click "Billing" (if you don't bind the bank card, you need to bind it first). In this section, we can choose a billing account for our project. And make it at a 'active' status.</br>
After these, we sussessfully create a project.

## Enable API
Here, we need to use the google natural language API so we need to activate this API in our project.

- First, we go back to our project list and click the project you just created, and click "Manage Project". 
- Click "ENABLE APIS AND SERVICES". Enter "Google Cloud Natural Language API" in the search box to search and find the required API. Then, we select the API and double-click, select "Enable" in the opened interface.

## Set up authentication/ Create credentials
Any client application that uses the API must be authenticated and granted access to the requested resources. This section describes important authentication concepts and provides steps for setting it up.<\br>
There are multiple options for authentication, but it is recommended that you use service accounts for authentication and access control. 
- In the cloud console, we go to the 'Create service account' page and select a project.
- In 'Service account name' field we enter a name. Then we can add a brief description of the account.
- After this, it will automatically generate a email address. You can find it in the Cloud Console. Click the email address for the service account that you created.
- Click 'Keys'. We choose create a new key, then the information of the key will be store in a JSON file and download to your computer.

## Configure local environment variables
