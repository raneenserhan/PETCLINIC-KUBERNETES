# SPRING-PETCLINIC-KUBERNETES <br/>

## About <br/><br/>
This is to run Petclinic Application using kubernetes deployment.<br/>
##### uses and creates following kubernetes components:<br/>
* kubernetes Deployment.
* kubernetes Service.

------------------------------------------------------------------------------------------------<br/>
## Pre-requisite:<br/><br/>

* The Docker compose file has already been built and attached.
* The Docker image pushed in dockerhub<br/>
https://hub.docker.com/r/raneenshub/spring-docker/tags?page=1&ordering=last_updated

------------------------------------------------------------------------------------------------<br/>

## RUN:<br/>
### Kubernetes ###<br/><br/>
1. Create the Deployment by running the following command:<br/>
`$ kubectl apply -f petclinic.yml`<br/><br/>
2. Run `kubectl get deployments` to check if the Deployment was created.<br/><br/>
3. open browser with url = https://localhost/8080
 ![pitclinic](https://user-images.githubusercontent.com/82150368/119245102-31762880-bb7f-11eb-83e6-25638c82367e.png)

------------------------------------------------------------------------------------------------<br/>
### Versions:
Kubernetes V1
