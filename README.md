# MC Mock Extension

### 1. What is this for?

The purpose is to provide a sample skeleton for building quality tools.

### 2. Setup
- a) Make sure you user has Copado User and Copado Job Engine, Quality Gate perm set assigned, and additionally Copado Admin license.
- b) Push the code
- c) Create the value "MC Mock Tool" in ExtensionConfiguration__c.ExtensionTool__c picklist, and also in "Copado Test Tool" global picklist value set. The first will be needed as the Extension Configuration is packaged with the value already set.
- d) Generate extension records, using the Copado Extensions page and the `MockMcExtensionBundle`.
- e) Ready to go! You can create your QG rules, extension configuration, tests, etc.
