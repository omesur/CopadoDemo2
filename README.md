# MC Mock Extension

### 1. What is this for?

The purpose is to provide a sample skeleton for building quality tools.

### 2. Setup
- a) Make sure your user has the following permission sets assigned: Copado User. Copado Job Engine, Quality Gate
- b) Make sure your user has the Copado Admin license.
- c) Push the code and components in this repository to your Org.
- d) Create the picklist value "MC Mock Tool" in ExtensionConfiguration__c.ExtensionTool__c picklist, and also in "Copado Test Tool" global picklist value set. The first will be needed as the Extension Configuration is packaged with the value already set.
- e) Go to Copado Extension Tab, select MockMCExtensionBundle from dropdown. 
- f) Click on Generate extension records
- e) You're ready to test this tool! You can create a test record manually, Quality Gate rules, extension configuration, etc.
