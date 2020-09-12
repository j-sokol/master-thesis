# Master Thesis

This thesis deals with design of a trip planner in geospatial graphs, with a limitation of routes in cities. Route planner offers various means of transport. Multiple ways of transport are combined into one single trip when certain combinations are used. Route planning service is designed using principles of so called microservices. Access to the planning results is designed using REST API. Technologies like Docker and Kubernetes are usually connected with microservices, those technologies will be used to deploy planner indo distributed and scallable system in the second part of the thesis.  While deploying the service in an distributed system an emphasis is taken on security of the whole architecture, therefore authentication and authorization into the system will be described in the work. Part of the thesis is dedicated to the application scalability,  with cases when servers or datacenters are down. Importance will be put on high availability of the application, both in usual day to day business and also while deploying the microservices.

## How to run

LaTeX has to be installed to create a `.pdf` file from source codes in this repository.

Jump to `src` directory, and then from there

```bash
pdflatex thesis.tex
```