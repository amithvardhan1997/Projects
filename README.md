# PROJECT-1
## Title:   Deployment of a Web Page
### Deployment of a web page using Amazon EC2 instance, GIT Hub and Nginx in the AWS Cloud Platform.
![P-1.png](images/p-1.png)
## Deployment Steps
1. **Amazon EC2 Instance Creation:**
   - Launch an EC2 instance on the AWS console.
   - Choose the appropriate instance type (T2 Micro), configure security groups, and obtain the key pair.
   - Connect to the server and
   - ```bash
     sudo-s # super user (root)
     ```
     ```bash
     apt-get update
     ```
     ```bash
     clear
     ```
2. **Nginx installation:**
   - ```bash
     apt-get install nginx -y
     ```
   - To check the Nginx status
   - ```bash
     systmctl status nginx #to start
     ```
   - To restart the nginx
   - ```bash
     systmctl restart nginx
   - After Nginx got installed go to the  nginx path ie.,
   - ```bash
     cd /var/www/html/
     ```
   - You can find the .html file there.
3. **Clone the Repository:**
   - Clone the Repository from the GIT Hub to the instance.
   - ```bash
     git clone https://github.com/your-username/your-repository.git
     ```
   - Now open that Repository
   - ```bash
     cd repository_name
     ```
   - Now 
