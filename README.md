[![continuas integration and deployment](https://github.com/abramReda/containusIntegration/actions/workflows/ci-cd.yaml/badge.svg)](https://github.com/abramReda/containusIntegration/actions/workflows/ci-cd.yaml)

# continuous Integration
in this learning project we try to make project to use **github actions** to make continuous Integration and deploy.  



in this project we focus only in writing [ci-cd.yaml](.github/workflows/ci-cd.yaml) 

with every commit to master bransh following steps will run automaticly by **github action**

1. make server with ubuntu 
2. install .net 5
3. restore any dependancy in our project
4. build application with .net
5. Run automated tests
6. deploy to Azure cloud
