----- This is currently a WIP -----

# Acorn workshop

Acorn is a simple application deployment framework for Kubernetes. It uses a simple format to specify an application running in containers allowing the application to be run, packaged and distributed in any environment and deployed to Kubernetes without needing to know much about it.

![logo](./images/acorn/acorn.jpeg)

In this workshop we will use a sample microservice application and show how we can build / run / package and distribute it using [Acorn](https://acorn.io).  

We will follow the steps below:  
  
- [Introduction to Acorn](./acorn.md)
- [Environment](./environment.md)
- [Sample application](./votingapp.md)
- [Write your first Acornfile](./acornfile.md)
- [Use Secret to secure connection to the db](./secret.md)
- [Use volumes to persist data](./volumes.md)
- [Build an distribute the application as an Acorn image](./acorn_image.md)
- [Development mode](./development_mode.md)  

Coming soon:
- Add TLS certificates (*)
- Use GitOps with ArgoCD

(*) this is only possible if workshop environment is running on a cloud provider
 
[Let's get started](./acorn.md)