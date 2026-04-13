## Oracle Weblogic Server:

Oracle WebLogic Server is a Java EE (Enterprise Edition) application server — a middleware platform used to develop, deploy, and run enterprise-scale applications.

WebLogic is Oracle's flagship application server for running Java-based enterprise applications. It serves as the foundation layer between your operating system/hardware and your business applications.


### Editions:

- **Standard Edition**: basic clustering
- **Enterprise Edition**: advanced clustering, high availability
- **Suite**: includes additional Oracle middleware components



### WebLogic Architecture:

| Concept | Description |
| ------- | ----------- |
| **Domain (Main Container)** | A domain is the top-level environment. Administrative unit grouping servers, resources, and apps |
| **Admin Server** | Central management node for a domain, used for configuration & management |
| **Managed Server** | Worker nodes that actually run applications | 
| **Node Manager** | Remote process for starting/stopping/monitoring servers | 



### WebLogic vs. alternatives:

| Server | Vendor | Notes | 
| ------ | ------ | ----- | 
| WebLogic | Oracle | Full Java EE, enterprise-grade |
| JBoss/WildFly | Red Hat | Open source alternative |
| WebSphere | IBM | IBM's enterprise equivalent |
| GlassFish | Eclipse/Oracle | Reference implementation |
| Tomcat | Apache | Lightweight, servlet-only |

