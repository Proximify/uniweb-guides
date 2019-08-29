# API Access

The UNIWeb API (application program interface) provides a simple way for other software systems to interact with UNIWeb. The objective of the API is to integrate UNIWeb within your existing software in order to eliminate the need to duplicate data, please see the following example.
 www.uniweb.network UNIWeb Administrator Guide 25
  Example
Your accounting software could access the API to automatically update its information whenever a researcher receives new funding and enters that data into UNIWeb. Similarly, your faculty website could access the API to automatically update its information whenever a professor adds a new publication and enters that data into UNIWeb.
Figure 19 API Access Page Overview ➀ Create a client
  7.1. Create an API Client
In order to authorize another system to interact with UNIWeb, it must first be provided with authorization. To do this, select the Create a Client option (see Figure 19). From this window you will be able to choose a name for your new client.
When you select the View option from the right of its row, you will see your client secret. This is the randomly generated password.
Any API clients that you create will inherit your UNIWeb permissions. This means that they will allow other systems to read or write any information that you currently have access to. In order to create these API clients,
Note: In order to create API clients, you require Create API Client permissions. For more information on roles, please see section 6.1.
www.uniweb.network UNIWeb Administrator Guide 26

 7.2. Remove an API Client
Figure 20 View Client Secret
To delete an API client from UNIWeb, select the Remove option from the right of its row. For more detailed information on the UNIWeb API, please visit http://proximify.ca/?api


