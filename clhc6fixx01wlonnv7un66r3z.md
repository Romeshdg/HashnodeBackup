---
title: "Connecting-the-Cloud-VNet-to-VNet-Peering-in-Microsoft-Azure"
datePublished: Sat May 06 2023 16:05:41 GMT+0000 (Coordinated Universal Time)
cuid: clhc6fixx01wlonnv7un66r3z
slug: connecting-the-cloud-vnet-to-vnet-peering-in-microsoft-azure
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1683388135256/200590e5-7ab9-4676-90ec-3f23bb987d93.png
tags: cloud, virtual-machine, azure, networking, azure-virtual-network-peering

---

> > > > # First Create a Virtual network For the Head office

[![Screenshot 2023-02-26 102338](https://user-images.githubusercontent.com/113555417/221437979-dd9263d8-5b9c-4cdd-94fc-4f2f1b76305d.jpg align="left")](https://user-images.githubusercontent.com/113555417/221437979-dd9263d8-5b9c-4cdd-94fc-4f2f1b76305d.jpg)

# Fill in Details as per Project requirements

[![Screenshot 2023-02-26 102510](https://user-images.githubusercontent.com/113555417/221437981-ae02b986-9db3-4779-bcf0-f3ab860ade25.jpg align="left")](https://user-images.githubusercontent.com/113555417/221437981-ae02b986-9db3-4779-bcf0-f3ab860ade25.jpg)

[![Screenshot 2023-02-26 102624](https://user-images.githubusercontent.com/113555417/221437982-ca9490db-e40d-4871-a298-15361951c8ad.jpg align="left")](https://user-images.githubusercontent.com/113555417/221437982-ca9490db-e40d-4871-a298-15361951c8ad.jpg)

# Set address range and create Subnet

[![Screenshot 2023-02-26 102645](https://user-images.githubusercontent.com/113555417/221437985-92e50ed4-656c-4d3b-bfb0-20485cf76b06.jpg align="left")](https://user-images.githubusercontent.com/113555417/221437985-92e50ed4-656c-4d3b-bfb0-20485cf76b06.jpg)

[![Screenshot 2023-02-26 102703](https://user-images.githubusercontent.com/113555417/221437986-6d383412-02dd-4f83-b9ca-2a76ea5ed25b.jpg align="left")](https://user-images.githubusercontent.com/113555417/221437986-6d383412-02dd-4f83-b9ca-2a76ea5ed25b.jpg)

[![Screenshot 2023-02-26 102742](https://user-images.githubusercontent.com/113555417/221437989-594419ca-edd8-428a-aa8e-64424da8948e.jpg align="left")](https://user-images.githubusercontent.com/113555417/221437989-594419ca-edd8-428a-aa8e-64424da8948e.jpg)

[![Screenshot 2023-02-26 103047](https://user-images.githubusercontent.com/113555417/221438052-8d498a5f-4cd1-481a-bf1a-5d0e8d183c95.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438052-8d498a5f-4cd1-481a-bf1a-5d0e8d183c95.jpg)

> > > > # Headoffice Network OverView

[![Screenshot 2023-02-26 103129](https://user-images.githubusercontent.com/113555417/221438058-353c3f7d-a928-486c-8f0e-f218cc1ba8d4.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438058-353c3f7d-a928-486c-8f0e-f218cc1ba8d4.jpg)

> > > > # Create Virtual Network for BranchOffice

[![Screenshot 2023-02-26 102842](https://user-images.githubusercontent.com/113555417/221438086-e05d219f-e29f-4a1f-a269-9e5a600f0d08.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438086-e05d219f-e29f-4a1f-a269-9e5a600f0d08.jpg)

[![Screenshot 2023-02-26 102956](https://user-images.githubusercontent.com/113555417/221438090-7b240e9c-a3b2-4290-aacd-59fcda3ac6f4.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438090-7b240e9c-a3b2-4290-aacd-59fcda3ac6f4.jpg)

# Set address range and create Subnet

[![Screenshot 2023-02-26 103008](https://user-images.githubusercontent.com/113555417/221438091-f60754f1-7187-4e85-bdab-cd2cd36d1070.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438091-f60754f1-7187-4e85-bdab-cd2cd36d1070.jpg)

[![Screenshot 2023-02-26 103028](https://user-images.githubusercontent.com/113555417/221438092-76aeaa34-3a33-4eaf-a0e4-3ae0de5bcf2f.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438092-76aeaa34-3a33-4eaf-a0e4-3ae0de5bcf2f.jpg)

[![Screenshot 2023-02-26 103102](https://user-images.githubusercontent.com/113555417/221438113-3fdf96ed-c9a9-4b46-8306-5be6c8f364fd.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438113-3fdf96ed-c9a9-4b46-8306-5be6c8f364fd.jpg)

> > > # BranchOffice Network

[![Screenshot 2023-02-26 103139](https://user-images.githubusercontent.com/113555417/221438116-5beec8f7-c73a-45cc-a563-1d4fca2cd107.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438116-5beec8f7-c73a-45cc-a563-1d4fca2cd107.jpg)

> > > > # Create a Virtual machine for the head Office And attach it with headoffice subnet

[![Screenshot 2023-02-26 103223](https://user-images.githubusercontent.com/113555417/221438198-9390b68d-51cc-4f04-8bd2-ddcf5579dd4d.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438198-9390b68d-51cc-4f04-8bd2-ddcf5579dd4d.jpg)

[![Screenshot 2023-02-26 103325](https://user-images.githubusercontent.com/113555417/221438199-d7d62417-85c4-4443-8b93-c5b0aad5d78a.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438199-d7d62417-85c4-4443-8b93-c5b0aad5d78a.jpg)

[![Screenshot 2023-02-26 103342](https://user-images.githubusercontent.com/113555417/221438202-0fc16d20-f41d-4765-a1d0-bacf35072985.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438202-0fc16d20-f41d-4765-a1d0-bacf35072985.jpg)

[![Screenshot 2023-02-26 103617](https://user-images.githubusercontent.com/113555417/221438203-85d1c18e-912e-4206-9921-8b67c4a4500d.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438203-85d1c18e-912e-4206-9921-8b67c4a4500d.jpg)

[![Screenshot 2023-02-26 103737](https://user-images.githubusercontent.com/113555417/221438204-953d5dbd-68d2-4c60-a816-0eeba3d8d815.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438204-953d5dbd-68d2-4c60-a816-0eeba3d8d815.jpg)

[![Screenshot 2023-02-26 103922](https://user-images.githubusercontent.com/113555417/221438205-66a234e7-1420-4553-9485-81c60b1ee1b5.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438205-66a234e7-1420-4553-9485-81c60b1ee1b5.jpg)

[![Screenshot 2023-02-26 103937](https://user-images.githubusercontent.com/113555417/221438208-361b7166-56bd-4027-a7d0-f55c6a240e48.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438208-361b7166-56bd-4027-a7d0-f55c6a240e48.jpg)

> > > > # Create a Virtual machine for Branch Office And attach wit branch office subnet

[![Screenshot 2023-02-26 105337](https://user-images.githubusercontent.com/113555417/221438209-fd67efe4-dd9f-480c-8c2b-e9a31b0e0f38.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438209-fd67efe4-dd9f-480c-8c2b-e9a31b0e0f38.jpg)

[![Screenshot 2023-02-26 105659](https://user-images.githubusercontent.com/113555417/221438218-98db4e69-2695-4148-b303-aeaa6547ee30.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438218-98db4e69-2695-4148-b303-aeaa6547ee30.jpg)

[![Screenshot 2023-02-26 105713](https://user-images.githubusercontent.com/113555417/221438219-b7da3bc0-6971-4990-9a39-05833fd16ef3.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438219-b7da3bc0-6971-4990-9a39-05833fd16ef3.jpg)

> > > > # Access Headoffice virtual machine through public ip using RDP

[![Screenshot 2023-02-26 105740](https://user-images.githubusercontent.com/113555417/221438266-3fe907d3-ea9e-4e14-9407-dad7001eaa39.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438266-3fe907d3-ea9e-4e14-9407-dad7001eaa39.jpg)

[![Screenshot 2023-02-26 105812](https://user-images.githubusercontent.com/113555417/221438270-66dd59ef-ccaf-452e-a257-b5d5fd98dc62.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438270-66dd59ef-ccaf-452e-a257-b5d5fd98dc62.jpg)

[![Screenshot 2023-02-26 105929](https://user-images.githubusercontent.com/113555417/221438271-5264b7ba-9e59-4a8d-8de0-d279967db013.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438271-5264b7ba-9e59-4a8d-8de0-d279967db013.jpg)

> > > > # Check Connection from aur Headoffice Virtual network to Branch office Virtual network

[![Screenshot 2023-02-26 110141](https://user-images.githubusercontent.com/113555417/221438274-e5bef2c7-e205-4429-8d00-f114108811ab.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438274-e5bef2c7-e205-4429-8d00-f114108811ab.jpg)

[![Screenshot 2023-02-26 110155](https://user-images.githubusercontent.com/113555417/221438276-69f80fa3-8c17-459c-9d66-54a591722397.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438276-69f80fa3-8c17-459c-9d66-54a591722397.jpg)

[![Screenshot 2023-02-26 110211](https://user-images.githubusercontent.com/113555417/221438277-8e74ee0e-3daf-4f14-bc8e-12db59114305.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438277-8e74ee0e-3daf-4f14-bc8e-12db59114305.jpg)

> > > > # **Add Peering Connections**

[![Screenshot 2023-02-26 110345](https://user-images.githubusercontent.com/113555417/221438313-35563bb2-937d-4a94-9f56-42f963aebe4a.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438313-35563bb2-937d-4a94-9f56-42f963aebe4a.jpg)

[![Screenshot 2023-02-26 110357](https://user-images.githubusercontent.com/113555417/221438315-399aa469-2b09-4b0e-a20b-60dd9967048c.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438315-399aa469-2b09-4b0e-a20b-60dd9967048c.jpg)

[![Screenshot 2023-02-26 110602](https://user-images.githubusercontent.com/113555417/221438316-760d981b-1e8f-4581-b2c4-84b87638bd52.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438316-760d981b-1e8f-4581-b2c4-84b87638bd52.jpg)

[![Screenshot 2023-02-26 110620](https://user-images.githubusercontent.com/113555417/221438318-67ee55ca-b036-4fdd-8791-7f863db2026e.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438318-67ee55ca-b036-4fdd-8791-7f863db2026e.jpg)

[![Screenshot 2023-02-26 110632](https://user-images.githubusercontent.com/113555417/221438319-bda2a82a-5151-4213-8b62-4840f7acd912.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438319-bda2a82a-5151-4213-8b62-4840f7acd912.jpg)

> > > > # Checking connection from Head office network to branch office network

[![Screenshot 2023-02-26 110710](https://user-images.githubusercontent.com/113555417/221438347-4809acf6-4f04-4e06-89ce-cfefab92fe9d.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438347-4809acf6-4f04-4e06-89ce-cfefab92fe9d.jpg)

[![Screenshot 2023-02-26 110724](https://user-images.githubusercontent.com/113555417/221438350-bbb6abfb-def3-4d0a-8b08-d4e889434cf9.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438350-bbb6abfb-def3-4d0a-8b08-d4e889434cf9.jpg)

[![Screenshot 2023-02-26 110825](https://user-images.githubusercontent.com/113555417/221438352-c0e3aed7-3aa9-429e-83c4-dcf3ff1edb8b.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438352-c0e3aed7-3aa9-429e-83c4-dcf3ff1edb8b.jpg)

[![Screenshot 2023-02-26 110847](https://user-images.githubusercontent.com/113555417/221438354-e94e3877-42b9-4e27-b7fd-3ad808359f5e.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438354-e94e3877-42b9-4e27-b7fd-3ad808359f5e.jpg)

[![Screenshot 2023-02-26 110859](https://user-images.githubusercontent.com/113555417/221438356-3f066df5-1ebe-42f1-b5f9-7cf236a84f70.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438356-3f066df5-1ebe-42f1-b5f9-7cf236a84f70.jpg)

[![Screenshot 2023-02-26 111030](https://user-images.githubusercontent.com/113555417/221438358-3c1c5623-c2d1-4c6f-9736-9d6c2f54fd41.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438358-3c1c5623-c2d1-4c6f-9736-9d6c2f54fd41.jpg)

[![Screenshot 2023-02-26 10047](https://user-images.githubusercontent.com/113555417/221438392-00b052a4-67c5-4f1c-9117-019edaf5c2f9.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438392-00b052a4-67c5-4f1c-9117-019edaf5c2f9.jpg)

[![Screenshot 2023-02-26 171812](https://user-images.githubusercontent.com/113555417/221438359-8bc3c2bc-befc-4a3b-b9ee-4ca3ebc49898.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438359-8bc3c2bc-befc-4a3b-b9ee-4ca3ebc49898.jpg)

[![Screenshot 2023-02-26 171840](https://user-images.githubusercontent.com/113555417/221438360-da01e779-e671-45fe-9ea8-62efd06f2b95.jpg align="left")](https://user-images.githubusercontent.com/113555417/221438360-da01e779-e671-45fe-9ea8-62efd06f2b95.jpg)

### ✔ Please check out my GitHub for more information and the code related to this project!

▶ GitHub Link   
 🔗[Romeshdg/Connecting-the-Cloud-VNet-to-VNet-Peering-in-Microsoft-Azure: VNet-to-VNet Peering in Microsoft Azure (](https://github.com/Romeshdg/Connecting-the-Cloud-VNet-to-VNet-Peering-in-Microsoft-Azure)[github.com](http://github.com)[)](https://github.com/Romeshdg/Connecting-the-Cloud-VNet-to-VNet-Peering-in-Microsoft-Azure)

📍 Thanks for reading, and happy learning! :) ✌

### ✨Let's continue to learn and grow together.

follow me on [LinkedIn](https://www.linkedin.com/in/romeshdharamgudi/) for more updates and insights. Also, don't forget to like, share, and comment on this post to spread the word and help others in their Learning journey.