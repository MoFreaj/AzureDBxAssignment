# Candidate’s Databricks Exercise 

We have created a resource group in an internal subscribtion for you. All what you have to do is to access the [portal.azure.com](https://portal.azure.com) : and then search for the resource group RG_[alias] where [alias] is alias@example.com in your email address.

If you couldn't locate the RG; please contact us.

All resources you are creating should be inside that resource group.

##The assignment is to:
1. Create your own virtual network.
1. Provision an Azure Databricks workspace injected in that virtual network previously created.
1. Create one or more clusters on your workspace that will allow you to complete the next steps.
1. Create an ADLS Gen 2 Storage account in azure portal.
1. Create a container in that storage and upload a random csv file to this container
1. Access/read the csv file as a dataframe in databricks using spark 
1. Create an external and managed delta table in the Databricks workspace 
   #Optional:
1. Create a Databricks Workflow which triggers a notebook with a streaming scenario perhaps… 
1. Trigger the previously created workflow using the Databricks Jobs API 
1. (Possibly Register a serve a model. Get predictions from the served model.) 
