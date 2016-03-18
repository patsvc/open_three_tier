#Open Three Tier Pattern

This repository contains the blueprint for the Open Three Tier pattern in IBM&reg; Bluemix&reg;. The Open Three Tier stack includes a high-availability Apache Tomcat proxy server, two load balanced Apache HTTP servers, and a MySQL database.

The _open-three-tier.yaml_ file is a HEAT Orchestration Template that contains definitions of the parameters and resources that are required to provision this stack to Bluemix. The stack components are provisioned into the Bluemix Virtual Servers service by using Salt formulas that are only accessible through Bluemix.
