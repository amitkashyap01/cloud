# Cloud Learning

## How to design an application
* Application should used asynchronous operations and event driven architecture so that main thread will remain responsive.
* Design loosly coupling
* Implement stateless components for scalability
* Cache content
* Implement API gateways to make backend functionality available to consumer applications
* Use federated identity management.
  * For example, use Firebase Authentication to authenticate users by using external identity providers.
* Implement health check endpoints 
  * For example, use stackdriver monitoring
* Setup logging and monitor your application's performance....use stackdriver apps
* Handle transient and long-lasting errors gracefully
* Consider data sovereignty and compliance requirements
* Functional and performance testing
* Perform high availability testing and develop disaster recovery plans
* Implement continous integration and delivery pipeline. Automate security checks
* Use strangler pattern to re-architect applications. i.e. incrementally replace components of the old application with new services.


## GCP development
* **Cloud Client Libraries** are the recommended way to make requests to a server. It receives performance benefits from gRPC APIs.
* **Cloud SDK** is a set of command line tools. It consists of gcloud, bq, gsutil
* **Cloud Shell**
* **Cloud developer IDE**
* **Firebase** is a mobile and web development plateform

