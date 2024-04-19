# AI Edge Terminology

## Near Edge
- Near edge typically refers to distributed deployments of “scaled-down” IT-like services to support business operations outside the core data centers and public cloud providers.[^1]. For the context, of RHOAI Edge use cases, these are OpenShift environments with additional restrictions for isolated networks and non-scalable resources.  These environment could be as small as Single Node OpenShift (SNO) environments or on-premise OpenShift clusters behind a customer

## Far Edge
- These are resource constrained environments with unreliable, extremely restricted or non-existent network connectivity with hardware resource constraints that greatly affect the architecture of the software and services running in each environment. 

## Model Server
- A Model Server is responsible for hosting models as a service to "to return predictions based on data inputs that you provide through API calls."[^3]
- For any workflows under opendatahub-io/ai-edge, we will be focusing on using the Model Servers and serving runtimes supported by Open Data Hub

## Model Registry & Model Source
- 

## Inference Containers / Inference Service Container Image
- Container images that package the model serving runtime together with the AI/ML model into a 

## Edge Restrictions

## Disconnected Environment

## Fleet Management

## Personas

### Data Scientist

### MLOps Engineer

### Cluster Admin

### Infrastructure Admin

## Pull Model

## GitOps - "GitOps uses Git repositories as a single source of truth to deliver infrastructure as code."[^2]

[^1]: https://www.redhat.com/en/blog/lets-level-set-at-the-edge "Let's Level Set at the Edge"
[^2]: https://www.redhat.com/en/topics/devops/what-is-gitops "What is GitOps"
[^3]: https://access.redhat.com/documentation/en-us/red_hat_openshift_ai_self-managed/2.8/html/serving_models/about-model-serving_about-model-serving "Red Hat OpenShift AI -> Serving models"
