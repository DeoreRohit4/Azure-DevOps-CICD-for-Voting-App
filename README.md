# Azure-DevOps-CICD-for-Voting-Application

![Screenshot from 2024-04-05 17-58-18](https://github.com/DeoreRohit4/Azure-DevOps-CICD-for-Voting-App/assets/102886808/ad38a830-6ef1-471e-b3b7-e1a5522e454e)

## Blog:- CI/CD Processes on Azure DevOps for a Voting Application
Link (CI PART): https://rohitexplainstech.hashnode.dev/cicd-processes-on-azure-devops-for-a-voting-application-ci-part
Link (CD PART): https://rohitexplainstech.hashnode.dev/cicd-processes-on-azure-devops-for-a-voting-application-cd-part

## Voting Application Architecture

![Architecture diagram](architecture.excalidraw.png)

* A front-end web app in [Python](/vote) which lets you vote between two options
* A [Redis](https://hub.docker.com/_/redis/) which collects new votes
* A [.NET](/worker/) worker which consumes votes and stores them in…
* A [Postgres](https://hub.docker.com/_/postgres/) database backed by a Docker volume
* A [Node.js](/result) web app that shows the results of the voting in real time

## Screenshots

![image](https://github.com/user-attachments/assets/f8cf9f38-0701-4a43-bf80-8ca2273325e3)
![image](https://github.com/user-attachments/assets/31cc72b2-8256-49c6-8579-0827758b4715)
![image](https://github.com/user-attachments/assets/3c605cc5-0c85-4867-bc3b-19ce85c03ba8)
![image](https://github.com/user-attachments/assets/971122fd-701f-484b-934e-47518dfec3ad)
![image](https://github.com/user-attachments/assets/3ea0baa0-ccd3-492f-b1ad-4a212bac039d)
![image](https://github.com/user-attachments/assets/9a20c4ba-9d7c-4977-96dd-fad290a69872)
![image](https://github.com/user-attachments/assets/2d511f01-55b9-4e51-b665-f41570fc6e0d)
![image](https://github.com/user-attachments/assets/e0e51fde-89cb-4e88-af3e-8bb6b1b1dc43)
![image](https://github.com/user-attachments/assets/b8bdacca-e18c-4889-b556-ba442f94b190)
