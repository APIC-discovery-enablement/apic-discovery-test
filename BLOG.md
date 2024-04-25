Discovering unmanaged APIs using API Connect - new feature

We are talking about APIC Discovery, a new feature of API Connect available only on the SaaS instances. 
Basically it can get a streamline of unmanaged APIs from static sources and recreate API contract from runtime data.

A possible use case would be a company X that runs hundreds, possible thousands of APIs on many backends and most of them are unmanged by a single API Manager software.
So the company X could use API Connect SaaS to both manage known APIs and using Discovery feature they can discover unmanaged APIs, automatically create documentation of those APIs and 
if they want they can import them in the API Connect manager and make them managed by APIC. They could also discover the unmanaged APIs, choose to not import them in the Manager
and let them unmanaged

apis still unmanaged but they can expose and manage APIs with documentation via Developer portal for your consumers


API discovery uses data source collectors that are placed onto gateways and ingresses to give you the visibility of the API traffic in your networks. 
The logs from this traffic are forwarded to the discovery capability, analyzed, and then API documents are generated and presented for review. 
These generated API documents can then be copied to draft APIs as required, to enable full lifecycle management and securely socializing them.

The following types of data source collectors are supported:

- GitHub
- DataPower® API Gateway proxy
- OpenTelemetry



<img width="998" alt="image" src="https://github.com/APIC-discovery-enablement/apic-discovery-test/assets/150448817/87aec6b9-5383-4d26-9065-eef8abb945f3">



PRODUCT FEEDBACK


source: https://www.ibm.com/docs/en/api-connect/saas?topic=applications-api-discovery
