---
title: "CI/CD Pipeline using Git, Jenkins, Maven, and Tomcat"
datePublished: Mon May 08 2023 17:06:47 GMT+0000 (Coordinated Universal Time)
cuid: clhf3hszj000509mn4xrkhnwk
slug: cicd-pipeline-using-git-jenkins-maven-and-tomcat
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1683565548868/b0b2cb8f-4fc4-4dc4-b75e-f31a0053c953.jpeg
tags: docker, maven, devops, jenkins, tomcat

---

## Step 1:-

•Setup a Linux EC2 Instance •Install Java •Install Jenkins •Start Jenkins •Access Web UI on port 8080

# Images:

# 01\. Setup a Linux EC2 Instance

[![Screenshot 2023-03-12 202227](https://user-images.githubusercontent.com/113555417/224949453-938219e1-292d-4e80-8bc5-ae5c9147c8ef.jpg align="left")](https://user-images.githubusercontent.com/113555417/224949453-938219e1-292d-4e80-8bc5-ae5c9147c8ef.jpg)

[![Screenshot 2023-03-12 202250](https://user-images.githubusercontent.com/113555417/224949466-b6fdfaf6-d7a0-4c34-a40e-80e12e985c86.jpg align="left")](https://user-images.githubusercontent.com/113555417/224949466-b6fdfaf6-d7a0-4c34-a40e-80e12e985c86.jpg)

[![Screenshot 2023-03-12 202354](https://user-images.githubusercontent.com/113555417/224949487-e6215e46-b04c-479e-b341-350d051004be.jpg align="left")](https://user-images.githubusercontent.com/113555417/224949487-e6215e46-b04c-479e-b341-350d051004be.jpg)

# 02\. Install JAVA , Jenkins and then start Jenkins

# 1

[![Screenshot 2023-03-12 200139](https://user-images.githubusercontent.com/113555417/224954549-69e14e7f-22a6-4153-a5f8-e0baaad07fdb.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954549-69e14e7f-22a6-4153-a5f8-e0baaad07fdb.jpg)

[![Screenshot 2023-03-12 200233](https://user-images.githubusercontent.com/113555417/224954576-7ec50a80-518b-4597-8c4d-4687f1890f60.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954576-7ec50a80-518b-4597-8c4d-4687f1890f60.jpg)

[![Screenshot 2023-03-12 200525](https://user-images.githubusercontent.com/113555417/224954591-d226a2a1-5ae9-44cb-9571-e8d3a6c52bf1.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954591-d226a2a1-5ae9-44cb-9571-e8d3a6c52bf1.jpg)

[![Screenshot 2023-03-12 200612](https://user-images.githubusercontent.com/113555417/224954600-bfacb188-3c52-4828-b277-2b1d69aadded.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954600-bfacb188-3c52-4828-b277-2b1d69aadded.jpg)

[![Screenshot 2023-03-12 200647](https://user-images.githubusercontent.com/113555417/224954612-a2addd1d-913b-4ed2-948d-d2b662dc023a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954612-a2addd1d-913b-4ed2-948d-d2b662dc023a.jpg)

# 2

[![Screenshot 2023-03-12 200729](https://user-images.githubusercontent.com/113555417/224954696-02d5336f-d001-4ddc-9c18-32ea3f6bc9bc.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954696-02d5336f-d001-4ddc-9c18-32ea3f6bc9bc.jpg)

[![Screenshot 2023-03-12 201055](https://user-images.githubusercontent.com/113555417/224954714-2cbf3dc2-baaf-4475-8fb8-d5d7738a364d.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954714-2cbf3dc2-baaf-4475-8fb8-d5d7738a364d.jpg)

[![Screenshot 2023-03-12 201126](https://user-images.githubusercontent.com/113555417/224954728-45bde64e-2ac6-44e0-88b9-714d1e739213.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954728-45bde64e-2ac6-44e0-88b9-714d1e739213.jpg)

[![Screenshot 2023-03-12 201143](https://user-images.githubusercontent.com/113555417/224954753-ff21a96b-7361-4699-b5a0-9ce1157bad07.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954753-ff21a96b-7361-4699-b5a0-9ce1157bad07.jpg)

[![Screenshot 2023-03-12 201335](https://user-images.githubusercontent.com/113555417/224954772-174f5c93-3422-4e8d-8c13-827fb507bfe3.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954772-174f5c93-3422-4e8d-8c13-827fb507bfe3.jpg)

[![Screenshot 2023-03-12 201353](https://user-images.githubusercontent.com/113555417/224954787-ff70b9d3-1f7f-4b46-8f0e-3a2b671939ed.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954787-ff70b9d3-1f7f-4b46-8f0e-3a2b671939ed.jpg)

[![Screenshot 2023-03-12 201445](https://user-images.githubusercontent.com/113555417/224954816-d7fe496b-36c1-44eb-bcfa-3c19740f81d4.jpg align="left")](https://user-images.githubusercontent.com/113555417/224954816-d7fe496b-36c1-44eb-bcfa-3c19740f81d4.jpg)

# 3

[![Screenshot 2023-03-12 201445](https://user-images.githubusercontent.com/113555417/224955021-a9b0afd1-aa11-43aa-9f9c-714e3166ce3d.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955021-a9b0afd1-aa11-43aa-9f9c-714e3166ce3d.jpg)

[![Screenshot 2023-03-12 201612](https://user-images.githubusercontent.com/113555417/224955110-0708a130-1c8c-4792-9a9f-3b84009b76da.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955110-0708a130-1c8c-4792-9a9f-3b84009b76da.jpg)

[![Screenshot 2023-03-12 202437](https://user-images.githubusercontent.com/113555417/224955122-40cb93eb-f03e-464c-8e92-2210d5fac8b8.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955122-40cb93eb-f03e-464c-8e92-2210d5fac8b8.jpg)

[![Screenshot 2023-03-12 202754](https://user-images.githubusercontent.com/113555417/224955136-5a80b5a1-c814-4130-9940-065655950505.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955136-5a80b5a1-c814-4130-9940-065655950505.jpg)

# 03\. Start Jenkins And Access Web UI on port 8080

[![Screenshot 2023-03-12 202816](https://user-images.githubusercontent.com/113555417/224955295-fe5d5de5-e664-4b5e-b0ef-6a99ca4a417a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955295-fe5d5de5-e664-4b5e-b0ef-6a99ca4a417a.jpg)

[![Screenshot 2023-03-12 202915](https://user-images.githubusercontent.com/113555417/224955331-d5757fe6-d1e9-41fb-88f1-021d049d6948.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955331-d5757fe6-d1e9-41fb-88f1-021d049d6948.jpg)

[![Screenshot 2023-03-12 203022](https://user-images.githubusercontent.com/113555417/224955348-09497e7f-57e1-40fa-94d4-e04a8471928c.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955348-09497e7f-57e1-40fa-94d4-e04a8471928c.jpg)

[![Screenshot 2023-03-12 203331](https://user-images.githubusercontent.com/113555417/224955363-4c506aed-81f1-4a3e-a940-72993b3cebe0.jpg align="left")](https://user-images.githubusercontent.com/113555417/224955363-4c506aed-81f1-4a3e-a940-72993b3cebe0.jpg)

## Step 2: Build Code

•Setup Maven on Jenkins Server •Setup Environment Variables •JAVA\_HOME, M2, M2\_HOME •Install Maven Plugin •Configure Maven and Java

# Images

# 01\. Setup Maven on Jenkins Server

[![Screenshot 2023-03-12 212344](https://user-images.githubusercontent.com/113555417/224957488-f31fe2b5-701b-4336-982e-ba85b893e61c.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957488-f31fe2b5-701b-4336-982e-ba85b893e61c.jpg)

[![Screenshot 2023-03-12 212452](https://user-images.githubusercontent.com/113555417/224957519-b9049d9d-52cf-4454-83d8-429b43449020.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957519-b9049d9d-52cf-4454-83d8-429b43449020.jpg)

[![Screenshot 2023-03-12 212511](https://user-images.githubusercontent.com/113555417/224957547-6fc15fe1-109b-41f0-99a2-fc0b9f5c6cc6.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957547-6fc15fe1-109b-41f0-99a2-fc0b9f5c6cc6.jpg)

[![Screenshot 2023-03-12 212601](https://user-images.githubusercontent.com/113555417/224957610-3ae92309-2244-4953-8f6f-cb752e567b87.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957610-3ae92309-2244-4953-8f6f-cb752e567b87.jpg)

[![Screenshot 2023-03-12 212623](https://user-images.githubusercontent.com/113555417/224957643-6ab4e6e9-6020-4997-a109-8eec7811e7f7.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957643-6ab4e6e9-6020-4997-a109-8eec7811e7f7.jpg)

[![Screenshot 2023-03-12 214923](https://user-images.githubusercontent.com/113555417/224957660-63d7e00f-7e31-49eb-a3f0-a8286c3351fb.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957660-63d7e00f-7e31-49eb-a3f0-a8286c3351fb.jpg)

[![Screenshot 2023-03-12 215102](https://user-images.githubusercontent.com/113555417/224957680-9b5a240c-29fd-48c0-9788-334f8e10886e.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957680-9b5a240c-29fd-48c0-9788-334f8e10886e.jpg)

[![Screenshot 2023-03-12 215156](https://user-images.githubusercontent.com/113555417/224957729-62e465ac-6a38-41e8-a683-0001deda837f.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957729-62e465ac-6a38-41e8-a683-0001deda837f.jpg)

[![Screenshot 2023-03-12 215401](https://user-images.githubusercontent.com/113555417/224957739-37a8c258-e6f6-4287-b6fa-ec641030917f.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957739-37a8c258-e6f6-4287-b6fa-ec641030917f.jpg)

# 02\. Setup Environment Variables

[![Screenshot 2023-03-12 215451](https://user-images.githubusercontent.com/113555417/224957925-924681bf-bc53-495e-a579-f7d15a6cad87.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957925-924681bf-bc53-495e-a579-f7d15a6cad87.jpg)

[![Screenshot 2023-03-12 215918](https://user-images.githubusercontent.com/113555417/224957944-a33c0875-7c08-412e-b3b5-eadbbb325014.jpg align="left")](https://user-images.githubusercontent.com/113555417/224957944-a33c0875-7c08-412e-b3b5-eadbbb325014.jpg)

# 03\. JAVA\_HOME, M2, M2\_HOME

[![Screenshot 2023-03-12 220947](https://user-images.githubusercontent.com/113555417/224958082-ba7ec1ec-9dfd-4728-bf24-7d8d11288dd2.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958082-ba7ec1ec-9dfd-4728-bf24-7d8d11288dd2.jpg)

[![Screenshot 2023-03-12 221224](https://user-images.githubusercontent.com/113555417/224958187-a231c55f-6915-4c5a-8c7d-acc0a2f98917.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958187-a231c55f-6915-4c5a-8c7d-acc0a2f98917.jpg)

# 04.Install Maven Plugin

[![Screenshot 2023-03-12 221415](https://user-images.githubusercontent.com/113555417/224958599-55033b7f-5768-478d-855c-60d63b98571a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958599-55033b7f-5768-478d-855c-60d63b98571a.jpg)

[![Screenshot 2023-03-12 221439](https://user-images.githubusercontent.com/113555417/224958619-192d51aa-010b-45bc-9aff-18a4f158cc15.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958619-192d51aa-010b-45bc-9aff-18a4f158cc15.jpg)

[![Screenshot 2023-03-12 221517](https://user-images.githubusercontent.com/113555417/224958634-67e2aa98-e922-411a-b1c2-73cdf7a295c2.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958634-67e2aa98-e922-411a-b1c2-73cdf7a295c2.jpg)

[![Screenshot 2023-03-12 221638](https://user-images.githubusercontent.com/113555417/224958653-1a867479-f452-4bdc-9fc6-18f872ba6b2d.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958653-1a867479-f452-4bdc-9fc6-18f872ba6b2d.jpg)

[![Screenshot 2023-03-12 221813](https://user-images.githubusercontent.com/113555417/224958666-d0cae476-db71-4db9-a8d1-c7fdb1e1e1f0.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958666-d0cae476-db71-4db9-a8d1-c7fdb1e1e1f0.jpg)

# 05\. Configure Maven and Java

[![Screenshot 2023-03-12 222603](https://user-images.githubusercontent.com/113555417/224958760-8d0ea7dc-0dfd-4b9d-a5c9-8b644d4d4713.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958760-8d0ea7dc-0dfd-4b9d-a5c9-8b644d4d4713.jpg)

[![Screenshot 2023-03-12 222617](https://user-images.githubusercontent.com/113555417/224958781-eb2b1106-6e4f-4a40-b554-2f8a162138c8.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958781-eb2b1106-6e4f-4a40-b554-2f8a162138c8.jpg)

[![Screenshot 2023-03-12 222813](https://user-images.githubusercontent.com/113555417/224958791-cc68e9ab-1ef3-4814-991a-6f0345c06c9d.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958791-cc68e9ab-1ef3-4814-991a-6f0345c06c9d.jpg)

[![Screenshot 2023-03-12 223136](https://user-images.githubusercontent.com/113555417/224958815-db0d199a-5ee1-4419-8eb1-4b0ddcdda3dc.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958815-db0d199a-5ee1-4419-8eb1-4b0ddcdda3dc.jpg)

[![Screenshot 2023-03-12 223159](https://user-images.githubusercontent.com/113555417/224958887-0dc90d3d-4f53-48c9-9579-f69a302f2c51.jpg align="left")](https://user-images.githubusercontent.com/113555417/224958887-0dc90d3d-4f53-48c9-9579-f69a302f2c51.jpg)

# 06\. Build

[![Screenshot 2023-03-12 223251](https://user-images.githubusercontent.com/113555417/224959106-3fb0ff8b-deb2-4088-9bfc-59ea69cf8609.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959106-3fb0ff8b-deb2-4088-9bfc-59ea69cf8609.jpg)

[![Screenshot 2023-03-12 223409](https://user-images.githubusercontent.com/113555417/224959120-e815f47b-ceef-4cfb-8fea-c31dcc39b996.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959120-e815f47b-ceef-4cfb-8fea-c31dcc39b996.jpg)

[![Screenshot 2023-03-12 223423](https://user-images.githubusercontent.com/113555417/224959236-74f477e6-c598-489f-99bf-fc7134215bb1.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959236-74f477e6-c598-489f-99bf-fc7134215bb1.jpg)

# 07\. Images

[![Screenshot 2023-03-12 223548](https://user-images.githubusercontent.com/113555417/224959386-17ff19a3-8fe1-4285-9135-51739b74eddf.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959386-17ff19a3-8fe1-4285-9135-51739b74eddf.jpg)

[![Screenshot 2023-03-12 223625](https://user-images.githubusercontent.com/113555417/224959409-f0ec4f0b-859b-4797-bbe8-afae49f99756.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959409-f0ec4f0b-859b-4797-bbe8-afae49f99756.jpg)

[![Screenshot 2023-03-12 223727](https://user-images.githubusercontent.com/113555417/224959442-308c088a-2194-4a00-bbd0-89336c9bbc2d.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959442-308c088a-2194-4a00-bbd0-89336c9bbc2d.jpg)

[![Screenshot 2023-03-12 223808](https://user-images.githubusercontent.com/113555417/224959524-ffecc019-b38c-44d4-b331-9df885582528.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959524-ffecc019-b38c-44d4-b331-9df885582528.jpg)

[![Screenshot 2023-03-12 223843](https://user-images.githubusercontent.com/113555417/224959536-2b2429ca-8723-49ab-931c-880d42ca3664.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959536-2b2429ca-8723-49ab-931c-880d42ca3664.jpg)

[![Screenshot 2023-03-12 223855](https://user-images.githubusercontent.com/113555417/224959541-63e2828a-2b2d-4dc1-a3f4-cfd565590a44.jpg align="left")](https://user-images.githubusercontent.com/113555417/224959541-63e2828a-2b2d-4dc1-a3f4-cfd565590a44.jpg)

## step 3: Integrate GitHub with Jenkins

•Install Git on Jenkins Instance •Install GitHub Plugin on Jenkins GUI •Configure Git on Jenkins GUI

# Images:

# 01\. Install Git on Jenkins Instance

[![Screenshot 2023-03-12 205453](https://user-images.githubusercontent.com/113555417/224960440-8d7b4e00-7206-4bf6-9266-9214fb52e259.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960440-8d7b4e00-7206-4bf6-9266-9214fb52e259.jpg)

[![Screenshot 2023-03-12 205636](https://user-images.githubusercontent.com/113555417/224960454-280ec4df-63b6-41e6-9aac-d773b2159a6a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960454-280ec4df-63b6-41e6-9aac-d773b2159a6a.jpg)

[![Screenshot 2023-03-12 205651](https://user-images.githubusercontent.com/113555417/224960477-27a4495e-bf78-4c21-ae45-911d8afb53a2.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960477-27a4495e-bf78-4c21-ae45-911d8afb53a2.jpg)

[![Screenshot 2023-03-12 205717](https://user-images.githubusercontent.com/113555417/224960489-274a89f6-4a08-4bfe-ae52-cda2ace2ee80.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960489-274a89f6-4a08-4bfe-ae52-cda2ace2ee80.jpg)

# 02\. Install GitHub Plugin on Jenkins GUI

[![Screenshot 2023-03-12 205801](https://user-images.githubusercontent.com/113555417/224960617-f3841de0-f959-43aa-9c54-8a1932b491d8.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960617-f3841de0-f959-43aa-9c54-8a1932b491d8.jpg)

[![Screenshot 2023-03-12 205833](https://user-images.githubusercontent.com/113555417/224960627-85b236e6-9afb-49ff-b9a2-090511e4dd1b.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960627-85b236e6-9afb-49ff-b9a2-090511e4dd1b.jpg)

[![Screenshot 2023-03-12 205857](https://user-images.githubusercontent.com/113555417/224960640-5735d35a-ea3a-4302-a070-83a7a55e2bdb.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960640-5735d35a-ea3a-4302-a070-83a7a55e2bdb.jpg)

[![Screenshot 2023-03-12 210025](https://user-images.githubusercontent.com/113555417/224960652-32071d67-ab56-4057-9ea0-05bbc5b212b1.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960652-32071d67-ab56-4057-9ea0-05bbc5b212b1.jpg)

[![Screenshot 2023-03-12 210054](https://user-images.githubusercontent.com/113555417/224960665-73d7ccb8-6d20-4454-a852-e706da4010c9.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960665-73d7ccb8-6d20-4454-a852-e706da4010c9.jpg)

[![Screenshot 2023-03-12 210247](https://user-images.githubusercontent.com/113555417/224960727-d93d9322-b280-43e8-9182-9a41375efcbe.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960727-d93d9322-b280-43e8-9182-9a41375efcbe.jpg)

# 03\. Configure Git on Jenkins GUI

[![Screenshot 2023-03-12 210321](https://user-images.githubusercontent.com/113555417/224960826-de4ebf6b-491a-4de2-ab7d-8a82f027b388.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960826-de4ebf6b-491a-4de2-ab7d-8a82f027b388.jpg)

[![Screenshot 2023-03-12 210526](https://user-images.githubusercontent.com/113555417/224960852-a8a05612-b1ca-408f-92ed-c36f27cfd01a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960852-a8a05612-b1ca-408f-92ed-c36f27cfd01a.jpg)

[![Screenshot 2023-03-12 210657](https://user-images.githubusercontent.com/113555417/224960868-bc4a5b4c-a7d6-410e-b976-841b1816d6ff.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960868-bc4a5b4c-a7d6-410e-b976-841b1816d6ff.jpg)

[![Screenshot 2023-03-12 210831](https://user-images.githubusercontent.com/113555417/224960877-22231309-a0e9-49dc-9353-903e3dce667c.jpg align="left")](https://user-images.githubusercontent.com/113555417/224960877-22231309-a0e9-49dc-9353-903e3dce667c.jpg)

## step 4: Deploy Artifacts on a Tomcat Server

•Setup a Linux EC2 Instance •Install Java •Download and configure Tomcat •Start Tomcat Server •Access Web UI on port 8080

# 01\. Setup a Linux EC2 Instance

[![Screenshot 2023-03-12 235439](https://user-images.githubusercontent.com/113555417/224961686-067472ff-9f44-4c90-a7a6-b214a1fdf04e.jpg align="left")](https://user-images.githubusercontent.com/113555417/224961686-067472ff-9f44-4c90-a7a6-b214a1fdf04e.jpg)

[![Screenshot 2023-03-12 235744](https://user-images.githubusercontent.com/113555417/224961699-aa8790cd-6575-4c2c-8d4e-66294d27c843.jpg align="left")](https://user-images.githubusercontent.com/113555417/224961699-aa8790cd-6575-4c2c-8d4e-66294d27c843.jpg)

# 02\. Install Java

[![Screenshot 2023-03-13 000605](https://user-images.githubusercontent.com/113555417/224961980-2eea6fc7-0d2f-4da4-be7f-20d7bf3a9854.jpg align="left")](https://user-images.githubusercontent.com/113555417/224961980-2eea6fc7-0d2f-4da4-be7f-20d7bf3a9854.jpg)

[![Screenshot 2023-03-13 001659](https://user-images.githubusercontent.com/113555417/224961991-b7d2e3a2-aaea-483f-b744-5e17aaea672f.jpg align="left")](https://user-images.githubusercontent.com/113555417/224961991-b7d2e3a2-aaea-483f-b744-5e17aaea672f.jpg)

[![Screenshot 2023-03-13 001905](https://user-images.githubusercontent.com/113555417/224962035-8bcd87cc-7f47-46c3-8112-6d2c22a0adb4.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962035-8bcd87cc-7f47-46c3-8112-6d2c22a0adb4.jpg)

# 03\. Download and configure Tomcat

[![Screenshot 2023-03-13 002022](https://user-images.githubusercontent.com/113555417/224962246-5c81078b-cc2b-4a20-abcb-3b206bbdaffe.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962246-5c81078b-cc2b-4a20-abcb-3b206bbdaffe.jpg)

[![Screenshot 2023-03-13 003147](https://user-images.githubusercontent.com/113555417/224962272-ec5b27fb-bd5d-4cb1-af2b-7fd634b16133.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962272-ec5b27fb-bd5d-4cb1-af2b-7fd634b16133.jpg)

[![Screenshot 2023-03-13 003301](https://user-images.githubusercontent.com/113555417/224962296-27b6c345-9bf5-4845-bf3f-b30076311125.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962296-27b6c345-9bf5-4845-bf3f-b30076311125.jpg)

[![Screenshot 2023-03-13 003411](https://user-images.githubusercontent.com/113555417/224962342-bf40da8a-0baa-4419-9644-b0c8016788c9.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962342-bf40da8a-0baa-4419-9644-b0c8016788c9.jpg)

[![Screenshot 2023-03-13 003446](https://user-images.githubusercontent.com/113555417/224962346-76a0f54c-b95c-4e50-b49e-70b0fe89ffc7.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962346-76a0f54c-b95c-4e50-b49e-70b0fe89ffc7.jpg)

[![Screenshot 2023-03-13 003506](https://user-images.githubusercontent.com/113555417/224962363-59fc5614-40fe-4a30-8e4e-bfc22acc1815.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962363-59fc5614-40fe-4a30-8e4e-bfc22acc1815.jpg)

# 04\. Start Tomcat Server and Access Web UI on port 8080

[![Screenshot 2023-03-13 003622](https://user-images.githubusercontent.com/113555417/224962750-9bc61987-1b1c-426e-892b-da98b15e8f2a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962750-9bc61987-1b1c-426e-892b-da98b15e8f2a.jpg)

[![Screenshot 2023-03-13 003701](https://user-images.githubusercontent.com/113555417/224962765-47809ca0-b634-4600-8091-b505cf682e01.jpg align="left")](https://user-images.githubusercontent.com/113555417/224962765-47809ca0-b634-4600-8091-b505cf682e01.jpg)

## Step 5: Integrate Tomcat with Jenkins

# Install “Deploy to container”

[![Screenshot 2023-03-13 010813](https://user-images.githubusercontent.com/113555417/224966871-9e106bb5-d373-48c1-ba78-899fd70b6e38.jpg align="left")](https://user-images.githubusercontent.com/113555417/224966871-9e106bb5-d373-48c1-ba78-899fd70b6e38.jpg)

[![Screenshot 2023-03-13 012906](https://user-images.githubusercontent.com/113555417/224966886-ef4a8cbd-b5b8-41a1-a1b9-5dd35be679b5.jpg align="left")](https://user-images.githubusercontent.com/113555417/224966886-ef4a8cbd-b5b8-41a1-a1b9-5dd35be679b5.jpg)

[![Screenshot 2023-03-13 012921](https://user-images.githubusercontent.com/113555417/224966912-8c0d0888-c16c-4a5c-bb62-47153915c5c7.jpg align="left")](https://user-images.githubusercontent.com/113555417/224966912-8c0d0888-c16c-4a5c-bb62-47153915c5c7.jpg)

# Configure tomcat server with Credentials

[![Screenshot 2023-03-13 020549](https://user-images.githubusercontent.com/113555417/224966938-5e947462-429f-4f93-8e61-cb875e3592f5.jpg align="left")](https://user-images.githubusercontent.com/113555417/224966938-5e947462-429f-4f93-8e61-cb875e3592f5.jpg)

[![Screenshot 2023-03-13 020636](https://user-images.githubusercontent.com/113555417/224967094-5afec37c-4ae8-4075-acb1-960280153328.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967094-5afec37c-4ae8-4075-acb1-960280153328.jpg)

[![Screenshot 2023-03-13 020851](https://user-images.githubusercontent.com/113555417/224967109-e596e2bc-909b-489a-92f1-5e7545ea847b.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967109-e596e2bc-909b-489a-92f1-5e7545ea847b.jpg)

[![Screenshot 2023-03-13 020913](https://user-images.githubusercontent.com/113555417/224967127-3c2dc270-537f-4184-8e96-1cfb083cd499.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967127-3c2dc270-537f-4184-8e96-1cfb083cd499.jpg)

[![Screenshot 2023-03-13 020927](https://user-images.githubusercontent.com/113555417/224967141-3b4ccbed-fcd7-4e53-9452-4cadef1c3069.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967141-3b4ccbed-fcd7-4e53-9452-4cadef1c3069.jpg)

[![Screenshot 2023-03-13 021020](https://user-images.githubusercontent.com/113555417/224967158-97b64ac7-8b90-49e6-9a1c-effd2e89efbd.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967158-97b64ac7-8b90-49e6-9a1c-effd2e89efbd.jpg)

[![Screenshot 2023-03-13 021326](https://user-images.githubusercontent.com/113555417/224967176-12805627-a597-4691-94b7-24e9859d8b02.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967176-12805627-a597-4691-94b7-24e9859d8b02.jpg)

[![Screenshot 2023-03-13 021344](https://user-images.githubusercontent.com/113555417/224967187-028976e2-fbec-4396-b5d9-391353dafe9a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967187-028976e2-fbec-4396-b5d9-391353dafe9a.jpg)

## Final

[![Screenshot 2023-03-13 021502](https://user-images.githubusercontent.com/113555417/224967354-f5b948f8-b393-4d11-a3f0-c2169146fa32.jpg align="left")](https://user-images.githubusercontent.com/113555417/224967354-f5b948f8-b393-4d11-a3f0-c2169146fa32.jpg)

### ✔ Please check out my GitHub for more information and the code related to this project!

▶ GitHub Link   
 🔗[Romeshdg/Simple-DevOps-Project (](https://github.com/Romeshdg/Simple-DevOps-Project)[github.com](http://github.com)[)](https://github.com/Romeshdg/Simple-DevOps-Project)

📍 Thanks for reading, and happy learning! :) ✌

### ✨Let's continue to learn and grow together.

follow me on [LinkedIn](https://www.linkedin.com/in/romeshdharamgudi/) for more updates and insights. Also, don't forget to like, share, and comment on this post to spread the word and help others in their Learning journey.