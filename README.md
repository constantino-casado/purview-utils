# purview-utils


## Description
Set of purview small tools based on python notebooks running on an Azure Synapse workspace.

The code in these notebooks might be used as a Boilerplate container to provide examples of code reusable for custom purposes.

## Execution environment
The code is designed to be run in a Synapse Spark environment

## Prerequisites
The code requires setting:
- A Synapse workspace capable of running Spark code
- A Service principal identity with contribuitor permissions in the Purview root collection
- A keyvault to manage the Service principal secret (as recommended in good practices) 

## Content
Right now you can find 2 notebooks, 
- One of them have code to list entities without schema in Purview for dedicated and serverless databases.
- The other notebook contains many support cells and is designed to capture descriptions from a lake database and write that information into Purview. 
