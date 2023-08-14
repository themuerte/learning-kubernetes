# Kubernetes

*Get info of this video: * [Kubernetes Tutorial for Beginners [FULL COURSE in 4 Hours]](https://www.youtube.com/watch?v=X48VuDVv0do)

## Components 

### Basic
- Pod: smallest unit of kunermetes or k8s 
- Node: a node is a worker machine in kubernetes and may be either a virtual machine or physical machine, depending on the cluster
- Service: In kubernetes, a service is a method for exposingg a network application that is running as one or more pods in your cluster
- Ingress: is an API object that helps developers exposer their applications and manage external access by providing http/s routing rules to the services within a kubernetes cluster

### Configurations

This is a part of configurations of pods in kubernetes, here two concepts how:
- ConfigMaps: A configmap is a API object thay stores configuration data for other obhects. It lets your decouple environment-specific configuration form contrainer images, so moving your applications gets easir
- Secrets: Similar to configmaps, kubernetes secrets are API objects specifically built to store confidential data. Kubernetes secrets contain small amounts of sensitive data, such a passwords, or kesy, This type of infomation might be put in pod specs or a container image.

### Volumenes

The volumens are storage on local machine or remote, or remote. One problem occurs when a container crashes or is stopped. Container state is not saved so all of the files that were created or modifies during the lifetime of the container are lost.

### Deployment and statefulSet

- Deployment: is how to create or modify intances of pods that hold a containerized application. Deployments can help to efficiently scale the number of repica pods, eneable the rollout of updated code in a controlled manner, or roll back to an earlier deployent version if necessary
- StatefulSets: is the workload PAI object used to menage stateful applications.
