# EX280-study
My study notes for Red Hat EX280 Certification (Openshift 4.12)

---

Here are some tasks I find relevant for the Red Hat EX280 Certification Exam

## Categories Covered In EX280

- Manage OpenShift Container Platform 

- Deploy applications 

- Manage storage for application configuration and data 

- Configure applications for reliability 

- Manage authentication and authorization

- Configure network security

- Enable developer self-service

- Manage OpenShift operators

- Configure application security
---

## My Lab Environment
My lab environment consists of a mix of Red Hat Coad Ready Containers (CRC) and the lab environment provided by EX280.  

My CRC environment is on OpenShift 4.13, and I found that the procedure for removing the kubeadmin account differs from 4.12 in the DO280 lab environment.  

Although all of these can be run on your CRC environment, the DO280 lab environment has some of the images I use to deploy, as well as NFS, set up ahead of time for testing Persistent Volume Claims (PVC) and some of the certs created for network security exercises. I may include certs/keys in this repo.
