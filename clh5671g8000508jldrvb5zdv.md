---
title: "Streamlined AKS {Kubernetes} Log Management with Vector and Azure Blob Storage"
datePublished: Mon May 01 2023 18:24:42 GMT+0000 (Coordinated Universal Time)
cuid: clh5671g8000508jldrvb5zdv
slug: streamlined-aks-kubernetes-log-management-with-vector-and-azure-blob-storage
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682591695778/8075c3ac-b2c8-4a16-be15-f4ef9b988cec.jpeg
tags: cloud, azure, cloud-computing, vector, aks

---

## **💡Highlights of this project:**

👨‍💻 Provisioned an AKS cluster using Azure portal or Azure CLI, enabling deployment and management of containerized applications in a highly available and scalable environment.

👩‍💻 Deployed an Nginx deployment in a test namespace of the AKS cluster, allowing testing of containerized applications and validating cluster functionality.

🤞 Created an Azure blob storage account and container named "akslogs" to store application logs securely and reliably, facilitating log analysis and troubleshooting.

💬 Configured Vector, a high-performance log collector, to access the Azure blob storage container and stream application logs using a configuration file called "vector-config.yaml", ensuring proper storage and analysis of logs.

📝 note:-Vector is a modern, open-source, and high-performance tool that simplifies the collection, processing, and routing of logs and metrics.

🚀Deploying and managing containerized applications using AKS, managing log storage using Azure blob storage, and utilizing Vector to collect and stream application logs for analysis.

✔ Please check out my GitHub for more information and the code related to this project!

▶ GitHub Link   
 🔗 [Romeshdg/Streaming-AKS-Kubernetes-Logs-to-Azure-Blob-Storage-using-Vector (](https://github.com/Romeshdg/Streaming-AKS-Kubernetes-Logs-to-Azure-Blob-Storage-using-Vector)[github.com](http://github.com)[)](https://github.com/Romeshdg/Streaming-AKS-Kubernetes-Logs-to-Azure-Blob-Storage-using-Vector)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071644045/12410ecf-e016-4cad-be41-d209f24e24db.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071651306/6f44e0b1-117a-456f-b61e-201b1a27f067.jpeg align="center")

# Azure CLI commands

`az group create --name MyResourceGroup --location central India`

`az aks create -g MyResourceGroup -n myAKSCluster --node-count 1 --generate-ssh-keys`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071699065/86f81915-e39e-4d1b-91e0-5e8d50843950.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071702036/be605908-4613-4cde-a57d-463a766ec60f.jpeg align="center")

## Step 2: Log in to the cluster and create a deployment

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071714728/4a750f21-72ea-44a7-9f76-02fc95c97829.jpeg align="center")

## Step 3: Create Azure blob storage to store the logs

`az storage account create --name storageromesh2002 --resource-group MyResourceGroup --location central India --sku Standard_ZRS --encryption-services blob`

`az storage container create --account-name storageromesh2002 --name akslogs \`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071770263/4eba879a-828b-4b39-a3fa-8649d825bf0e.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071773474/87900ce1-1754-46f7-967e-1f8a47661cd2.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071775606/97e2e731-6816-44b6-9dd9-ca2b8acc8766.jpeg align="center")

## Step4: Storage Account Connection String

### overview:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071790867/3b74bdba-4fb2-40e3-acce-0a901ab8a2d1.jpeg align="center")

## Step 5: Prepare vector-config.yaml

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071803516/db68fc0a-3cc0-41ed-ad11-776af2ad9e41.jpeg align="center")

## Step 6: Install Vector using Helm

helm repo add vector [https://helm.vector.dev](https://helm.vector.dev) helm repo update helm upgrade --install vector vector/vector -f vector-config.yaml -n test-ns --version 0.17.1

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071823174/488e804d-18c3-4021-9711-b7d077db2cba.jpeg align="center")

## Step 7: The moment of truth!

After a few minutes see the logs streaming to the “akslogs” container in your Azure Blob Storage.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071847720/89524a20-1326-4888-a451-952b5180bfc8.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071851430/b2a9754f-65e0-4898-a7eb-8f9b05bdff1d.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071854149/ea3e9532-2bc3-4805-b45b-04cfefa3ee22.jpeg align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679071859158/8944d855-4fc0-4920-a474-fe67c7fb0315.jpeg align="center")

# ✅ Overall, this project can help organizations effectively manage and leverage their AKS logs for various use cases, such as troubleshooting, performance optimization, security, compliance, and business intelligence.

### 📍 Thanks for reading, and happy learning! :) ✌

### ✨Let's continue to learn and grow together.

follow me on [LinkedIn](https://www.linkedin.com/in/romeshdharamgudi/) for more updates and insights. Also, don't forget to like, share, and comment on this post to spread the word and help others in their Learning journey.