---
title: "Efficient and Scalable Application Delivery with Azure Load-Balancer and  Virtual-Machine"
datePublished: Tue May 09 2023 16:30:39 GMT+0000 (Coordinated Universal Time)
cuid: clhghn67a07t6a7nvbeg59mem
slug: efficient-and-scalable-application-delivery-with-azure-load-balancer-and-virtual-machine
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1683611896812/66669bd8-138e-4f8b-b01b-5f06cb538700.webp
tags: virtual-machine, azure, learning, networking, load-balancer

---

## Deploy webserver with Load Balancer And VM Scale Set

# Diagram-1

[![Screenshot 2023-02-25 182443](https://user-images.githubusercontent.com/113555417/221364325-72f405bc-2128-4709-a893-cb5ba580dc9a.jpg align="left")](https://user-images.githubusercontent.com/113555417/221364325-72f405bc-2128-4709-a893-cb5ba580dc9a.jpg)

# Diagram-2

[![Screenshot 2023-02-25 182409](https://user-images.githubusercontent.com/113555417/221364336-f6d90472-22b9-4d63-8a09-efe2b55a9a1f.jpg align="left")](https://user-images.githubusercontent.com/113555417/221364336-f6d90472-22b9-4d63-8a09-efe2b55a9a1f.jpg)

> > > > # Create a Virtual Machine Scale set

# Fill in details as per Project requirements

[![Screenshot 2023-02-25 121521](https://user-images.githubusercontent.com/113555417/221364619-a0447a20-a8c0-4781-b5fa-fd42075999e6.jpg align="left")](https://user-images.githubusercontent.com/113555417/221364619-a0447a20-a8c0-4781-b5fa-fd42075999e6.jpg)

> > > > # VMSS OverView

[![Screenshot 2023-02-25 170423](https://user-images.githubusercontent.com/113555417/221365664-dceeecd2-a647-44aa-9f82-8ab43857bb34.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365664-dceeecd2-a647-44aa-9f82-8ab43857bb34.jpg)

> > > > # Instances
> > > > 
> > > > # Create a Virtual Machine with a Public Ip address

[![Screenshot 2023-02-25 140851](https://user-images.githubusercontent.com/113555417/221364773-7032bda5-802e-4399-90a9-d86d0c8f6f86.jpg align="left")](https://user-images.githubusercontent.com/113555417/221364773-7032bda5-802e-4399-90a9-d86d0c8f6f86.jpg)

> > > > # Overview

[![Screenshot 2023-02-25 170515](https://user-images.githubusercontent.com/113555417/221364829-729443c5-41fd-44c3-9dcf-b5e216efbd3d.jpg align="left")](https://user-images.githubusercontent.com/113555417/221364829-729443c5-41fd-44c3-9dcf-b5e216efbd3d.jpg)

> > > > # Access our public Virtual Machine through RDP & install IIS server and VMSS instances access through private Ip using RDP

[![Screenshot 2023-02-25 132011](https://user-images.githubusercontent.com/113555417/221365332-59a7b6de-72ae-4fe1-b5fb-1d59006f72c4.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365332-59a7b6de-72ae-4fe1-b5fb-1d59006f72c4.jpg)

> > > > # Create Load Balancer

[![Screenshot 2023-02-25 170530](https://user-images.githubusercontent.com/113555417/221365787-6b3e4c96-8ae1-4558-80a2-f939fc07a205.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365787-6b3e4c96-8ae1-4558-80a2-f939fc07a205.jpg)

> > > > # Frontend Ip configure

[![Screenshot 2023-02-25 170551](https://user-images.githubusercontent.com/113555417/221365792-870eed8c-018a-4dba-bcc7-c685629f3303.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365792-870eed8c-018a-4dba-bcc7-c685629f3303.jpg)

> > > > # Backend Pool

[![Screenshot 2023-02-25 170609](https://user-images.githubusercontent.com/113555417/221365794-c4de2240-9f9d-48be-bde3-4ea82efd0a30.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365794-c4de2240-9f9d-48be-bde3-4ea82efd0a30.jpg)

> > > > # Add Virtual Machine

[![Screenshot 2023-02-25 170626](https://user-images.githubusercontent.com/113555417/221365815-33546f14-66d4-4a5e-8585-04ca8b00c12d.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365815-33546f14-66d4-4a5e-8585-04ca8b00c12d.jpg)

> > > > # Health Prob

[![Screenshot 2023-02-25 170700](https://user-images.githubusercontent.com/113555417/221365820-50329e93-f7fa-42c5-ad73-2282f700eb79.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365820-50329e93-f7fa-42c5-ad73-2282f700eb79.jpg)

> > > > # LoadBalancer Rule

[![Screenshot 2023-02-25 170717](https://user-images.githubusercontent.com/113555417/221365823-720c06d2-62e2-406f-a5d8-5808a401af12.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365823-720c06d2-62e2-406f-a5d8-5808a401af12.jpg)

> > > > # NatRule

[![Screenshot 2023-02-25 170735](https://user-images.githubusercontent.com/113555417/221365825-603b3dda-01dc-48dc-b1ef-b73874501f8a.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365825-603b3dda-01dc-48dc-b1ef-b73874501f8a.jpg)

> > > > # Check Server Using Frontend Ip

[![Screenshot 2023-02-25 172143](https://user-images.githubusercontent.com/113555417/221365911-6d952633-1781-4c5c-a106-68f9ff800b53.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365911-6d952633-1781-4c5c-a106-68f9ff800b53.jpg)

> > > > # Virtual Machine Scale Set Rule

# Custom autoscale

[![Screenshot 2023-02-25 173529](https://user-images.githubusercontent.com/113555417/221365965-84453f89-4010-430e-8f39-a624e4b774c5.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365965-84453f89-4010-430e-8f39-a624e4b774c5.jpg)

> > > > # Scale Rule

[![Screenshot 2023-02-25 173947](https://user-images.githubusercontent.com/113555417/221365970-6f32058a-a23d-4ccb-8a86-8d5a20561171.jpg align="left")](https://user-images.githubusercontent.com/113555417/221365970-6f32058a-a23d-4ccb-8a86-8d5a20561171.jpg)

> > > > # Create a.bat file and Run a.bat file for Checking autoscale working or not

[![Screenshot 2023-02-25 175506](https://user-images.githubusercontent.com/113555417/221366107-232ce01d-ae71-4a7f-b087-46ffa651a40f.jpg align="left")](https://user-images.githubusercontent.com/113555417/221366107-232ce01d-ae71-4a7f-b087-46ffa651a40f.jpg)

> > > > # Final Diagrams

[![Screenshot 2023-02-25 182357](https://user-images.githubusercontent.com/113555417/221366139-6df0e0bb-b838-4c7e-b777-bd43e2301aa2.jpg align="left")](https://user-images.githubusercontent.com/113555417/221366139-6df0e0bb-b838-4c7e-b777-bd43e2301aa2.jpg)

[![Screenshot 2023-02-25 182427](https://user-images.githubusercontent.com/113555417/221366141-521137f6-0aad-40c5-a9de-288f96f5c964.jpg align="left")](https://user-images.githubusercontent.com/113555417/221366141-521137f6-0aad-40c5-a9de-288f96f5c964.jpg)

### ✔ Please check out my GitHub for more information and the code related to this project!

▶ GitHub Link   
 🔗[Romeshdg/Efficient-and-Scalable-Application-Delivery-with-Azure-Load-Balancer-and-Virtual-Machine: Deploy webserver with Load Balancer And Vm Scale Set (](https://github.com/Romeshdg/Efficient-and-Scalable-Application-Delivery-with-Azure-Load-Balancer-and-Virtual-Machine)[github.com](http://github.com)[)](https://github.com/Romeshdg/Efficient-and-Scalable-Application-Delivery-with-Azure-Load-Balancer-and-Virtual-Machine)

📍 Thanks for reading, and happy learning! :) ✌

### ✨Let's continue to learn and grow together.

follow me on [LinkedIn](https://www.linkedin.com/in/romeshdharamgudi/) for more updates and insights. Also, don't forget to like, share, and comment on this post to spread the word and help others in their Learning journey.