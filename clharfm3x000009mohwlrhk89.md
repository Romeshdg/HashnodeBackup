---
title: "Seamless Web App Hosting with Nginx and Docker"
datePublished: Fri May 05 2023 16:18:05 GMT+0000 (Coordinated Universal Time)
cuid: clharfm3x000009mohwlrhk89
slug: seamless-web-app-hosting-with-nginx-and-docker
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1683303440307/188e6104-a5df-426c-9252-f325c6e76e98.png
tags: docker, aws, nginx, devops, load-balancing

---

# Highlights of this project:

🚀Deployed a web application using an Nginx server within a Docker container.

🚀Configured a reverse proxy with Nginx to act as a gateway between outside requests and the application server.

🚀Set up a DNS subdomain to make the application accessible to users.

🚀Used popular tech stack including Amazon EC2, GitHub, Docker, Nginx.

🚀This project was a great learning experience for deploying web applications using the Nginx server within a Docker container.

✔ Please check out my GitHub for more information and the code related to this project!

▶ GitHub Link   
 🔗[Romeshdg/django-notes-app (](https://github.com/Romeshdg/django-notes-app)[github.com](http://github.com)[)](https://github.com/Romeshdg/django-notes-app)

## Steps :

Clone the Project repo:

```plaintext
git clone https://github.com/sanket363/Nginx-project.git
```

# Step 1:Launch an instance

note :- Add inbound traffic rules for HTTP, and HTTPS in addition to SSH.

[![Screenshot 2023-03-12 001119](https://user-images.githubusercontent.com/113555417/224932334-cbbbc4e8-3bfc-4dc6-bda9-82b0062777fa.jpg align="left")](https://user-images.githubusercontent.com/113555417/224932334-cbbbc4e8-3bfc-4dc6-bda9-82b0062777fa.jpg)

## Step 2: Install Nginx on this server by using the following command.

Update your package index:

```plaintext
sudo apt-get update
```

Install NGINX using apt-get:

```plaintext
sudo apt-get install nginx
```

Once the installation is complete, start the NGINX service:

```plaintext
sudo systemctl start nginx
```

To verify that NGINX is running, check its status:

```plaintext
sudo systemctl status nginx
```

# Images :

[![Screenshot 2023-03-11 212551](https://user-images.githubusercontent.com/113555417/224932539-985f3dde-721d-4087-93f0-9915eb1d426c.jpg align="left")](https://user-images.githubusercontent.com/113555417/224932539-985f3dde-721d-4087-93f0-9915eb1d426c.jpg)

[![Screenshot 2023-03-11 212638](https://user-images.githubusercontent.com/113555417/224932548-102efe5a-1329-40d5-9a3e-5b2d1d33aef5.jpg align="left")](https://user-images.githubusercontent.com/113555417/224932548-102efe5a-1329-40d5-9a3e-5b2d1d33aef5.jpg)

[![Screenshot 2023-03-11 212704](https://user-images.githubusercontent.com/113555417/224932566-788dd22a-f788-4d4c-8d07-75ea3d554a55.jpg align="left")](https://user-images.githubusercontent.com/113555417/224932566-788dd22a-f788-4d4c-8d07-75ea3d554a55.jpg)

[![Screenshot 2023-03-11 213023](https://user-images.githubusercontent.com/113555417/224932581-d6584939-9ef8-4f6d-8cf2-78b65517158a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224932581-d6584939-9ef8-4f6d-8cf2-78b65517158a.jpg)

## Step 3: To check the working status of the Nginx server

You should see output indicating that the service is active and running.

NGINX should start automatically after a reboot. To enable this, run:

```plaintext
sudo systemctl enable nginx
```

## status

[![Screenshot 2023-03-11 213219](https://user-images.githubusercontent.com/113555417/224932679-a1ba7cf2-0bd6-4c29-accf-dc86827c7efb.jpg align="left")](https://user-images.githubusercontent.com/113555417/224932679-a1ba7cf2-0bd6-4c29-accf-dc86827c7efb.jpg)

# Step 4: View the homepage details stored in the index file on its path /var/www/html.

[![Screenshot 2023-03-11 213504](https://user-images.githubusercontent.com/113555417/224933058-aa69856c-103c-4921-80a7-d95913a841b5.jpg align="left")](https://user-images.githubusercontent.com/113555417/224933058-aa69856c-103c-4921-80a7-d95913a841b5.jpg)

# Step 5: Installation and configuration files of the Nginx server can be seen at /etc/nginx path where

[![Screenshot 2023-03-11 213656](https://user-images.githubusercontent.com/113555417/224933184-e701d38e-0f94-4bdc-acd5-77aacc9fe0bb.jpg align="left")](https://user-images.githubusercontent.com/113555417/224933184-e701d38e-0f94-4bdc-acd5-77aacc9fe0bb.jpg)

[![Screenshot 2023-03-11 213656](https://user-images.githubusercontent.com/113555417/224933516-47f8019d-5438-45a1-ac8b-2bf2f50efa77.jpg align="left")](https://user-images.githubusercontent.com/113555417/224933516-47f8019d-5438-45a1-ac8b-2bf2f50efa77.jpg)

[![Screenshot 2023-03-11 214116](https://user-images.githubusercontent.com/113555417/224933527-ceb1307e-0a58-46d4-a507-4b60d670237e.jpg align="left")](https://user-images.githubusercontent.com/113555417/224933527-ceb1307e-0a58-46d4-a507-4b60d670237e.jpg)

# Step 6:Cloning the source code to this server using Git.

[![Screenshot 2023-03-11 220503](https://user-images.githubusercontent.com/113555417/224933793-6c30de77-5478-45f4-931c-76a9ca86c621.jpg align="left")](https://user-images.githubusercontent.com/113555417/224933793-6c30de77-5478-45f4-931c-76a9ca86c621.jpg)

## Step 7: Docker Installation

Install Docker using apt-get:

```plaintext
sudo apt-get install docker.io
```

Add your current user to the docker group:

```plaintext
sudo usermod -aG docker $USER
```

Reboot the system to apply the changes:

```plaintext
sudo reboot
```

Images:

[![Screenshot 2023-03-11 220747](https://user-images.githubusercontent.com/113555417/224934366-147c079c-25cc-4cee-9a61-fca8535f7a67.jpg align="left")](https://user-images.githubusercontent.com/113555417/224934366-147c079c-25cc-4cee-9a61-fca8535f7a67.jpg)

[![Screenshot 2023-03-11 221025](https://user-images.githubusercontent.com/113555417/224934587-919fce8d-db87-47c8-b91b-2fb11ea485d1.jpg align="left")](https://user-images.githubusercontent.com/113555417/224934587-919fce8d-db87-47c8-b91b-2fb11ea485d1.jpg)

[![Screenshot 2023-03-11 221149](https://user-images.githubusercontent.com/113555417/224934611-b13c431f-b64e-4ba5-a2e0-1bea09c74265.jpg align="left")](https://user-images.githubusercontent.com/113555417/224934611-b13c431f-b64e-4ba5-a2e0-1bea09c74265.jpg)

[![Screenshot 2023-03-11 221231](https://user-images.githubusercontent.com/113555417/224934633-138182ca-db31-409f-8a46-94bfaaf9855e.jpg align="left")](https://user-images.githubusercontent.com/113555417/224934633-138182ca-db31-409f-8a46-94bfaaf9855e.jpg)

## step 8: Building and Running Docker Container

Navigate to the directory that contains your Dockerfile and run the following command to build the container:

```plaintext
sudo docker build -t my-notes-app:latest .
```

To run the container and map port 8000 on the container to port 8000 on the host, run the following command:

```plaintext
sudo docker run -p 8000:8000 my-notes-app:latest
```

Images:

[![Screenshot 2023-03-11 221446](https://user-images.githubusercontent.com/113555417/224934793-d87e42fa-2b7e-4db1-bf96-a4e39b766c93.jpg align="left")](https://user-images.githubusercontent.com/113555417/224934793-d87e42fa-2b7e-4db1-bf96-a4e39b766c93.jpg)

[![Screenshot 2023-03-11 221638](https://user-images.githubusercontent.com/113555417/224934811-d1dc450b-46c0-4b47-8f4b-4b009a503f88.jpg align="left")](https://user-images.githubusercontent.com/113555417/224934811-d1dc450b-46c0-4b47-8f4b-4b009a503f88.jpg)

## Step 9: Configuring NGINX

NGINX's configuration files are located in the /etc/nginx/ directory. The main configuration file is nginx.conf. Before making any changes to this file, make a backup copy:

```plaintext
sudo cp /etc/nginx/nginx.conf /etc/nginx/nginx.conf.bak
```

To apply any changes you make to the configuration files, you'll need to restart NGINX:

```plaintext
sudo systemctl restart nginx
```

To add a proxy pass configuration for your Docker container, navigate to the sites-enabled path on Ubuntu:

```plaintext
cd /etc/nginx/sites-enabled/
```

Use the following command to open the default file in Vim:

```plaintext
sudo vim default
```

Find the `location /` block and inside the curly braces, add the following line to create a proxy pass to your Docker container:

```plaintext
proxy_pass http://127.0.0.1:8000;
```

Add another `location` block for proxy the API requests to the container:

```plaintext
location /api {
  proxy_pass http://127.0.0.1:8000/api;
}
```

Images:

[![Screenshot 2023-03-11 221446](https://user-images.githubusercontent.com/113555417/224936736-622b7186-68cc-40d1-b110-99d4e5aaef0f.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936736-622b7186-68cc-40d1-b110-99d4e5aaef0f.jpg)

[![Screenshot 2023-03-11 221638](https://user-images.githubusercontent.com/113555417/224936754-9cdb58cb-8d9c-4495-bdd2-e71f793c227a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936754-9cdb58cb-8d9c-4495-bdd2-e71f793c227a.jpg)

[![Screenshot 2023-03-11 222303](https://user-images.githubusercontent.com/113555417/224936848-aedb31f3-11b7-4e57-af40-c2addec1176c.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936848-aedb31f3-11b7-4e57-af40-c2addec1176c.jpg)

[![Screenshot 2023-03-11 222354](https://user-images.githubusercontent.com/113555417/224936860-02d5e7c6-a25d-43cb-bc95-82c1a24a8983.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936860-02d5e7c6-a25d-43cb-bc95-82c1a24a8983.jpg)

[![Screenshot 2023-03-11 223134](https://user-images.githubusercontent.com/113555417/224936875-4342bb5a-aed7-46a3-923a-21439378fca0.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936875-4342bb5a-aed7-46a3-923a-21439378fca0.jpg)

[![Screenshot 2023-03-11 223716](https://user-images.githubusercontent.com/113555417/224936890-4d7ffe45-c0cf-494c-b41d-14842db6af97.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936890-4d7ffe45-c0cf-494c-b41d-14842db6af97.jpg)

[![Screenshot 2023-03-11 224045](https://user-images.githubusercontent.com/113555417/224936900-f921b2a9-c104-4c8c-a320-fc9e27af6045.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936900-f921b2a9-c104-4c8c-a320-fc9e27af6045.jpg)

[![Screenshot 2023-03-11 224601](https://user-images.githubusercontent.com/113555417/224936954-7546920f-55a7-4d38-b5d5-aaa46f7bbaed.jpg align="left")](https://user-images.githubusercontent.com/113555417/224936954-7546920f-55a7-4d38-b5d5-aaa46f7bbaed.jpg)

[![Screenshot 2023-03-11 225253](https://user-images.githubusercontent.com/113555417/224937073-f69fce7b-5f40-4fee-952e-110ba671c71a.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937073-f69fce7b-5f40-4fee-952e-110ba671c71a.jpg)

[![Screenshot 2023-03-11 225306](https://user-images.githubusercontent.com/113555417/224937088-ea9404fb-cf8c-4c00-9fd3-9362a5963657.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937088-ea9404fb-cf8c-4c00-9fd3-9362a5963657.jpg)

[![Screenshot 2023-03-11 225517](https://user-images.githubusercontent.com/113555417/224937118-442143da-55d3-48ae-932c-87df4ab6734d.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937118-442143da-55d3-48ae-932c-87df4ab6734d.jpg)

After saving above changes in default file now navigate to the /var/www/html/ location and do below commands:

```plaintext
mkdir static
```

```plaintext
cp -r /home/<your-user>/Nginx-project/mynotes/build/static/* /var/www/html/static/
```

Iamges:

[![Screenshot 2023-03-11 225811](https://user-images.githubusercontent.com/113555417/224937128-ef1b3429-5a72-4508-b43c-41931594dbc3.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937128-ef1b3429-5a72-4508-b43c-41931594dbc3.jpg)

[![Screenshot 2023-03-11 230133](https://user-images.githubusercontent.com/113555417/224937153-20af61a0-a2dc-4e19-934f-3a2212b612cb.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937153-20af61a0-a2dc-4e19-934f-3a2212b612cb.jpg)

[![Screenshot 2023-03-11 230133](https://user-images.githubusercontent.com/113555417/224937680-773c889f-8e1e-403d-a4ba-ae0d68e52c14.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937680-773c889f-8e1e-403d-a4ba-ae0d68e52c14.jpg)

[![Screenshot 2023-03-11 230151](https://user-images.githubusercontent.com/113555417/224937692-969c0251-4a39-419c-8c85-298aa9394b63.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937692-969c0251-4a39-419c-8c85-298aa9394b63.jpg)

[![Screenshot 2023-03-11 230401](https://user-images.githubusercontent.com/113555417/224937714-9c810c20-8dbc-4fce-8e7a-bff403392068.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937714-9c810c20-8dbc-4fce-8e7a-bff403392068.jpg)

[![Screenshot 2023-03-11 230740](https://user-images.githubusercontent.com/113555417/224937743-fd07c966-5f6a-4bb1-ba65-58598ab10431.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937743-fd07c966-5f6a-4bb1-ba65-58598ab10431.jpg)

[![Screenshot 2023-03-11 230904](https://user-images.githubusercontent.com/113555417/224937760-c98d74c3-009a-4730-8d11-4c4fbaf54a77.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937760-c98d74c3-009a-4730-8d11-4c4fbaf54a77.jpg)

[![Screenshot 2023-03-11 231734](https://user-images.githubusercontent.com/113555417/224937769-819842aa-12bb-4286-9118-729d6811c9a0.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937769-819842aa-12bb-4286-9118-729d6811c9a0.jpg)

# Once done restart the nginx service

```plaintext
systemctl restart nginx
```

[![Screenshot 2023-03-11 231857](https://user-images.githubusercontent.com/113555417/224937834-a58e5a77-078d-4720-81be-e62fdde0a718.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937834-a58e5a77-078d-4720-81be-e62fdde0a718.jpg)

Now navingate to your browser and go to the url

```plaintext
http://<public-ip>/
```

[![Screenshot 2023-03-11 235939](https://user-images.githubusercontent.com/113555417/224937978-28ce2d99-8844-4531-9484-a00fbd6b034f.jpg align="left")](https://user-images.githubusercontent.com/113555417/224937978-28ce2d99-8844-4531-9484-a00fbd6b034f.jpg)

The technology stack used in this project included Amazon EC2, GitHub, Docker, and Nginx. Amazon EC2 provided the virtual server that hosted our application, GitHub allowed us to store and version control our application code, Docker allowed us to package and deploy our application in a containerized environment, and Nginx provided the web server and reverse proxy functionality.

# Overall, this project demonstrated how Nginx Server can be used to deploy web applications in a scalable, secure, and reliable manner, and how Docker can be used to package and deploy these applications with ease.

### 📍 Thanks for reading, and happy learning! :) ✌

### ✨Let's continue to learn and grow together.

follow me on [LinkedIn](https://www.linkedin.com/in/romeshdharamgudi/) for more updates and insights. Also, don't forget to like, share, and comment on this post to spread the word and help others in their Learning journey.