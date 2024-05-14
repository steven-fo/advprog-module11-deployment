# advprog-module11-deployment
Module 11 Advanced Programming 2023/2024


## Hello Minikube
1. Run before and after expose service
#### Before
![image](https://github.com/steven-fo/advprog-module11-deployment/assets/119484321/825642b1-a386-4916-9634-a681b5d47c18)

#### After
![image](https://github.com/steven-fo/advprog-module11-deployment/assets/119484321/6f04618e-b37d-4147-a294-e74d941db4d3)

Before expose of the service, it doesnt show any logs whenever there are any open browser. After the exposal of the service, it began to accept request. Those requests can be seen in the logs as shown in the picture above.

2. The -n stands for namespace. So, by declaring -n, we instruct the terminal to search for the service with the namespace that we want.
