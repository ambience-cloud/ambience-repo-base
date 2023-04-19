# Ambience Git Repository Base

This repository contains basic ambience artifacts which contains useful steps for housekeeping and scheduling of clean up ETLs to initialize Ambience setup. 

## Ambience docker
You may request for an evaluation copy of Ambience from support@elixirtech.com

## Deploy artifacts in a new Ambience installation

### Git Deploy 
- Navigate to Ambience Service Chooser -> Git Deploy Module.
- In the Git Deploy, select Git Pull section and set Repository from local to remote. And select the git branch init. 
- Trigger a pull action.
- This pull all the artifacts from github repository and replace all in Ambience system
- The modules that has the change are 
   * ETL module with housekeeping jobs
   * Config module with reference configs  
   * Scheduler Triggers
   
### Take owner artifacts to user admin 
Before you can use the artifacts, you will need take ownship. 

* Navigate to Ambience Service Chooser -> Ownership Module.
* Select ETL Chainset tab, check "Show All Users" to see the new housekeeping ETL chainsets, select all the steps and click "Reassign" button and reassign to the current user i.e. admin.
* Select Trigger tab, check "Show All Users" to see the new Trigger chainset, select all the trigger and click "Reassign" button and reassign to the current user i.e. admin.






