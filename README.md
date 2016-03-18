#Open Three Tier Pattern

This repository contains the blueprint for the Open Three Tier pattern in IBM&reg; Bluemix&reg;. The Open Three Tier stack includes a high-availability Apache Tomcat proxy server, two load balanced Apache HTTP servers, and a MySQL database.

The _open-three-tier.yaml_ file is a HEAT Orchestration Template that contains definitions of the parameters and resources that are required to provision this stack to Bluemix. The stack components are provisioned into the Bluemix Virtual Servers service by using Salt formulas that are only accessible through Bluemix.

# Text for the Bluemix Tile

Use this blueprint to quickly provision and deploy a three-tier web application.
* The blueprint is predefined with the stack components and architecture, including a high-availability Apache Tomcat proxy server, two load-balanced Apache HTTP servers, and a MySQL database.
* You can customize the blueprint to meet your application needs. Add your application components to the stack, and then quickly the stack into the Bluemix VM service and iterate changes in the live environment.
* Your iterative changes to the blueprint and application source code are stored in Git repositories. By storing your infrastructure and application code together, you can easily standardize, maintain, and replicate your environments across development, testing, and production environments.
