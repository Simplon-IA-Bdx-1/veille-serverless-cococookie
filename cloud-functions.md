# Serverless et Cloud-functions

## Services

- AWS => AWS Lambda
- Google Cloud Platform => GC Functions
- Ms Azure  => Azure Functions
- IBM Cloud => IBM Cloud functions
- ...

## Server vs. Serveless

Server

- Server
- VM
- AdminSys
- Gérés par nous

Serverless

- FaaS (Functions as a Service) 
- Code that runs on event-driven, **ephemeral** and **stateless** environments, fully managed by a third-party.

## Pro

- Simplicité de gestion des environnements
- Gestion et maintenance à la charge du fournisseur de cloud
- Cost
- Infinite scale
- Packaging (.zip with code and libraries)

## Cons

- Contôle réduit sur l'appli
- Limite de temps d'execution (300 s a la louche)
- Accessibles seulement via API privée
- Architecture plus complexe
- Tests en local (diffiuclté)
- Vendor lock-in


## Webographie

- Serverless explained by [css-tricks](https://serverless.css-tricks.com/)
- [calculateur de coûts](http://serverlesscalc.com/)
- [source](https://www.gocd.org/2017/06/26/serverless-architecture-continuous-delivery/)  image archi
- [pros and cons](https://hackernoon.com/what-is-serverless-architecture-what-are-its-pros-and-cons-cc4b804022e9)