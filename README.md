# Azure-DevOps-CICD-for-Voting-Application

![Screenshot from 2024-04-05 17-58-18](https://github.com/DeoreRohit4/Azure-DevOps-CICD-for-Voting-App/assets/102886808/ad38a830-6ef1-471e-b3b7-e1a5522e454e)

## Blog:- CI/CD Processes on Azure DevOps for a Voting Application
Link: https://rohitexplainstech.hashnode.dev/cicd-processes-on-azure-devops-for-a-voting-application-ci-part

## Voting Application Architecture

![Architecture diagram](architecture.excalidraw.png)

* A front-end web app in [Python](/vote) which lets you vote between two options
* A [Redis](https://hub.docker.com/_/redis/) which collects new votes
* A [.NET](/worker/) worker which consumes votes and stores them in…
* A [Postgres](https://hub.docker.com/_/postgres/) database backed by a Docker volume
* A [Node.js](/result) web app that shows the results of the voting in real time


