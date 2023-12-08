# Helm_Charts

Referred to the KodeKloud Voting Application git repo: 
https://github.com/kodekloudhub/example-voting-app-kubernetes/tree/main

Created Helm charts using te deployment and service files.

Pre-Requisite: Install Helm.
Steps to use this Helm Charts:
1) Create a namespace of your choice.
2) Run the following commands:
    helm install <release-name> charts-voting-res -n <namespace>
    helm install <release-name> charts-voting-fe -n <namespace>
3) Verify if all the pods,deployments and services are created successfully.
4) Port-forward the two front-end applications and verify, if the application opens up and gives the expected output as seen in the screenshot attached below.

- On selecting Cat:
   ![image](https://github.com/Janemils/Helm_Charts/assets/143650941/fa3a41c8-b1d5-4111-8ad6-81a42a37d5d1)
   ![image](https://github.com/Janemils/Helm_Charts/assets/143650941/2eefe6ad-b341-45cb-964e-86e0bb66e339)

- On selecting Dog:
  ![image](https://github.com/Janemils/Helm_Charts/assets/143650941/c7a2afe4-e43c-4b26-9689-531271caf5f6)
  ![image](https://github.com/Janemils/Helm_Charts/assets/143650941/0cd2b913-cd20-4684-86c4-e7f061614b88)


