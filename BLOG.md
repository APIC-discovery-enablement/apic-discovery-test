  Discovering unmanaged APIs using API Connect - new feature
  
  We are talking about APIC Discovery, a new feature of API Connect available only on the SaaS instances. 
  Basically it can get a streamline of unmanaged APIs from static sources and recreate API contract from runtime data.
  
  USE CASE
  This could potentially open many business opportunities API Connect SaaS to many different industries and companies:
  a possible use case for this new feature would be a company X that runs hundreds, possible thousands of APIs on many backends and most of them are unmanged by a single API Manager software.
  The company X could use API Connect SaaS to both manage known APIs and using Discovery feature they can discover unmanaged APIs, automatically create documentation of those APIs and if they want they can import them in the API Connect manager and make them managed by APIC. They could also discover the unmanaged APIs, choose to not import them in the Manager and let them unmanaged but still expose them
  through the IBM API Connect Developer portal with the documentation to make them available for consumers.
  
  NONAME OVERLAP?
  One can argument that there is an overlap with NoName discovery feature, it can discover unamanged APIs too. So why a client would choose IBM API Connect - Discovery over NoName?
  
  Let's deep dive a little bit:
  API Connect discovery feature uses data source collectors that are placed onto gateways and ingresses to give you the visibility of the API traffic in your networks. 
  The logs from this traffic are forwarded to the discovery capability, analyzed, and then API documents are generated and presented for review. 
  These generated API documents can then be copied to draft to review them and eventually to enable full lifecycle management and securely socializing them. As already said one it is also possible to expose them via Developer portal without make them managed by the API Manager, in this way consumers of the portal can access the documentation but of course they can not subscribe, at this time.
  
  The following types of data source collectors are supported:
  
  - GitHub
  - DataPower API Gateway proxy
  - OpenTelemetry
  
  <img width="998" alt="image" src="https://github.com/APIC-discovery-enablement/apic-discovery-test/assets/150448817/87aec6b9-5383-4d26-9065-eef8abb945f3">
  
  
  This means that not only it can discover APIs on runtime through DataPower gateway and OpenTelemetry logs, but it also can look into GitHub repositories and discover unmanaged/unused APIs, even if they are never called, so it is a static data source.
  This partially answer the question above, in fact NoName can only discover APIs on runtime. Imagine the company X has a huge, not updated, GitHub repository: there could be unsecured or very old unmanaged APIs that could potentially expose the backends to risk.
  
  
  
  Manage the unmanaged APIs
  As already noted above the unmanaged discovered APIs can be imported as a draft and then can be fully manage through the API Manager.
  For example imagine that the company X do not manage the backend service of these unamanged APIs but thanks to the proxy data source
  
  
  
  
  
  PRODUCT FEEDBACK
  
  
  source: https://www.ibm.com/docs/en/api-connect/saas?topic=applications-api-discovery
