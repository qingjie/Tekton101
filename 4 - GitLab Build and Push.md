Tekton supports source code to be built from GitLab. This short tutorial demonstrates a NodeJS application to be built from GitLab and the image to be pushed in Docker hub.

### Prerequisites

* A Kubernetes cluster: Any Kubernetes cluster will do. To get a free cluster on IBM Cloud, [follow this link](https://www.ibm.com/cloud/kubernetes-service).
* Installation of [Tekton CLI](https://github.com/tektoncd/cli) on your machine.
* Installation of [latest Tekton Pipelines release](https://github.com/tektoncd/pipeline/blob/master/docs/install.md#installing-tekton-pipelines).
* A GitLab repo to pull the source code from and a Docker Hub (or any other image registry) to push the image to.
