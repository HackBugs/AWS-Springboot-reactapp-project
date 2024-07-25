# AWS-Springboot-reactapp-project
# Author: HackBugs

- ### SDLC
- ------
- Plan
- Implement
- Test
- Deploy
- Maintain
 
- ### Faceboook
- ---------------
- Programming 
- software testing
- 	automatic testing
- 	manual testing
- Release of software / After testing complate
- Operations
 
- ### Development and operations
- ----------------------------
- Downtime
- Handale huge traffic

- #### Development people knowledge of
- 	Programming languages
- 	Test Prameworks
- 	Databases
- 	Virsion control
 	
- ### Operations people knowledge OF
- 	OS, Mostly Linux
- 	command-line
- 	scripting
- 	monitoring tools
	
- ----------------------------------
- ### Commit code - TEST - BUILD - PUSH - DEPLOY
- ------------ CI/CD PIPELINE ---------------
- 
- Traditional WATERFALL Meathod
- --------------------------------
- Requirements
- Development
- Testing
- Operations
			
- Waterfall vs Agile methology
- ---------------------------------

- ### Agile Methology
- --------------------
-  Contionus integration
-  Contionus Delivery
 
- Implement
- Test
- Build
- Deploy
- Maintain

- ### linux
- -----------
- Intro to operating system
- Virtualization
- Linux file system
- linux file system
- main linux commands
- package manager
- wroking with vim editor
- user $ permission
- shell scripting
- environment variable
- networking
- SSH - Secure shell

- install packages on linux distro ----
 Debain based
--------------
```sh
This all use apt and apt-get
 Ubuntu
 debain
 mint
```
- Red Hat Based
- -----------------
```
This all use yum
 Rhel
 centos
 fedora
```
- -----------------------------------------------------------------------------
### Software spring boot suite 4

- ### i downloaded a project of Springboot and react of backend and frontend
- now install all inviroment which requred like - jdk, nodejs,  maven, gradle
- 
- JDK - https://www.oracle.com/java/technologies/javase-jdk11-downloads.html
- nodjs - https://nodejs.org/en
- gradle - https://gradle.org/releases/
- maven - https://maven.apache.org/download.cgi
 
- ### cmd to check
- ------------
- java -version

- ### nodejs 
- ---------
- node -v
- npm -v

- mvn --version
- gradle -v
 
- ### after downloding project from github paste your requred folder
- and that with cmd cd/ enter the folder location like there should be to folder
- one springboot-backend  and second react-frontend

- Follow this steps -
- -----------------------

- ### Great! Since you have already installed JDK, Maven, Node.js, and Gradle, and your project is located at - `C:\my-website\ReactJS-Spring-Boot-CRUD-Full-Stack-App-master`, here's a detailed step-by-step guide to run the Spring Boot backend and React frontend.
 
- ### Step-by-Step Guide
- #### 1. Open Command Prompt
 
- Press `Win + R`, type `cmd`, and hit Enter to open the Command Prompt.
 
- #### 2. Navigate to the Project Directory
 
 ```sh
- cd C:\my-website\ReactJS-Spring-Boot-CRUD-Full-Stack-App-master
```

- #### 3. Run the Spring Boot Backend
 
- 1. **Navigate to the backend directory**:
-    - Assuming the backend files are in a folder named `backend` or something similar inside the main project directory.
    
   ```sh
    cd backend  # Adjust according to your project structure
 ```
 
- 2. **Build and run the Spring Boot application**:
-    - For Maven:
-      ```sh
     mvn clean install
     mvn spring-boot:run
      ```
 
-    - For Gradle:
      ```sh
      gradlew build
      gradlew bootRun
      ```

- 3. **Check if the Spring Boot application is running**:
-    - Open a web browser and go to `http://localhost:8080`. You should see the Spring Boot application running.
 
- #### 4. Run the React Frontend
- 
- 1. **Open a new Command Prompt window**.
 
- 2. **Navigate to the frontend directory**:
-    - Assuming the frontend files are in a folder named `frontend` or something similar inside the main project directory.
    
    ```sh
    cd C:\my-website\ReactJS-Spring-Boot-CRUD-Full-Stack-App-master\frontend  # Adjust according to your project structure
    ```

- 3. **Install dependencies**:
    ```sh
     npm install
    ```
 
- 4. **Start the React application**:
    ```sh
    npm start
    ``` 
- 5. **Check if the React application is running**:
-    - Open a web browser and go to `http://localhost:3000`. You should see the React application running.
 
- ### Troubleshooting
 
- - **Port conflicts**: Ensure no other applications are running on ports `8080` (Spring Boot) and `3000` (React).
- - **Environment variables**: Ensure that the required environment variables are set correctly.
- - **Logs**: Check the terminal or command prompt logs for any errors or warnings and address them as needed.
 
- ### Summary of Commands

- 1. **Navigate to the project directory**:
    ```sh
    cd C:\my-website\ReactJS-Spring-Boot-CRUD-Full-Stack-App-master
    ```
 
- 2. **Run Spring Boot backend**:
-    - For Maven:
-      ```sh
-      cd backend
-      mvn clean install
-      mvn spring-boot:run
      ```
-    - For Gradle:
-      ```sh
-      cd backend
-      gradlew build
-      gradlew bootRun
      ```
 
- 3. **Run React frontend**:
    ```sh
    cd C:\my-website\ReactJS-Spring-Boot-CRUD-Full-Stack-App-master\frontend
    npm install
    npm start
    ```
 
- By following these steps, you should be able to run and check your Spring Boot backend and React frontend project on your PC.
-  If you encounter any issues, feel free to ask for further assistance!
  
- ### after installing everything like jdk, nodejs, maven, gradle, set environment vriable 
-  enter the springboot backend folder run this cmd - gradle init than user other cmds
  
- ### A Gradle build's root directory should contain one of the possible settings 
- files: settings.gradle, settings.gradle.kts, settings.gradle.dcl.It may also contain one of the
- possible build files: build.gradle, build.gradle.kts, build.gradle.dcl.
 
- To create a new Gradle build in this directory run 'gradle init'
 
- ---------------------------------------------------------------------

### install gradle 
- ommand 'gradle' not found, but can be installed with:
- sudo snap install gradle  # version 7.2, or
- sudo apt  install gradle  # version 4.4.1-13
- See 'snap info gradle' for additional versions.

```sh
cd path\to\your\springboot-project

Using Maven:
---------------
mvn clean install
mvn spring-boot:run

Using Gradle:
--------------
gradle build
gradle bootRun

const apiBaseUrl = 'http://localhost:8080';
```
-------------------------------------------------------

Node.js, JDK, Maven, aur Gradle development tools hain jo aapke application ka code likhne, build karne, aur locally run karne ke liye use hote hain. DevOps ka role ise ek step aage le jaata hai jahan automation, deployment, aur monitoring involved hoti hai. Main aapko explain karta hoon DevOps ka role aur unki tools ke bare mein:

### DevOps Role in Application Lifecycle:

1. **Source Code Management**:
   - **Git** aur **GitHub**: Aap apna code version control system mein rakhte ho. Developers apne code ko Git repository mein push karte hain.

2. **Continuous Integration (CI)**:
   - **Jenkins**: Jaise hi code repository mein koi changes aati hain, Jenkins automatically build aur test process trigger karta hai. Isse ensure hota hai ki code changes safe hain aur application build properly ho rahi hai.

3. **Build Automation**:
   - **Maven/Gradle**: Yeh tools aapke Java-based Spring Boot application ko build karne ke liye use hote hain. Jenkins in tools ko automate karta hai taaki manual intervention ki zarurat na ho.

4. **Containerization**:
   - **Docker**: Application ko containerize karke, aap usko easily deploy aur manage kar sakte hain across different environments (development, testing, production).

5. **Continuous Deployment (CD)**:
   - **Jenkins** aur **Docker**: Jenkins build aur tests pass hone ke baad Docker images ko deploy karta hai. Yeh automated process aapki application ko consistent aur reliable way mein deploy karta hai.

6. **Infrastructure as Code (IaC)**:
   - **Terraform**: Infrastructure (jaise servers, databases, networks) ko code ke form mein manage karne ke liye use hota hai. Terraform scripts aapki infrastructure ko automate aur replicate karne mein help karte hain.

7. **Configuration Management**:
   - **Ansible**: Servers aur applications ki configuration automate karne ke liye use hota hai. Isse aap multiple servers par configuration changes easily apply kar sakte hain.

8. **Monitoring and Logging**:
   - **Prometheus** aur **Grafana**: Aapki application aur infrastructure ki monitoring ke liye use hote hain. Yeh tools aapko real-time metrics aur alerts provide karte hain.
   - **ELK Stack (Elasticsearch, Logstash, Kibana)**: Logs ko collect, analyze aur visualize karne ke liye use hota hai.

9. **Reverse Proxy and Load Balancing**:
   - **Nginx**: Production environment mein aapki application ko scale karne aur efficiently manage karne ke liye use hota hai. Yeh incoming traffic ko different services mein route karta hai.

### Example Workflow with DevOps:

1. **Development**:
   - Developers apna code likhte hain aur Git repository mein push karte hain.

2. **Build and Test**:
   - Jenkins automatically build aur test pipeline ko trigger karta hai.
   - Maven/Gradle build tools ko use karke application build hoti hai aur tests run hote hain.

3. **Containerization**:
   - Docker use karke application ko containerize kiya jata hai.

4. **Deployment**:
   - Jenkins Docker images ko production environment mein deploy karta hai.
   - Nginx use karke reverse proxy aur load balancing setup hota hai.

5. **Monitoring and Logging**:
   - Prometheus aur Grafana use karke application aur infrastructure ki monitoring hoti hai.
   - ELK Stack use karke logs ko collect aur analyze kiya jata hai.

### Summary:

- **Development Tools (Node.js, JDK, Maven, Gradle)**: Code likhne aur build karne ke liye.
- **DevOps Tools (Git, Jenkins, Docker, Terraform, Ansible, Prometheus, Grafana, Nginx)**: Automation, deployment, monitoring, aur infrastructure management ke liye.

DevOps ka main goal hai ki development aur operations teams ke beech collaboration aur communication improve ho, processes automate ho, aur application reliable aur fast deliver ho end-users tak.
-----------------------------------------------------------------------------------

AWS pe React aur Spring Boot project ko deploy karne ke liye hum poora DevOps roadmap follow karenge. Ye steps aapko shuru se leke last tak har cheez setup karne me help karenge. Aapko sab kuch Ubuntu (EC2 instance) pe karna hoga.

### Step-by-Step Guide:

#### 1. AWS Account Setup
- **Sign up for an AWS Account**: Agar aapka AWS account nahi hai toh [AWS sign-up page](https://aws.amazon.com/) pe jaake account create karein.

#### 2. EC2 Instance Launch
1. **Launch an EC2 Instance**:
   - AWS Management Console me login karein.
   - "EC2" service select karein.
   - "Launch Instance" pe click karein.
   - Instance type: Choose `t2.micro` (Free tier eligible).
   - AMI: Select `Ubuntu Server 22.04 LTS`.
   - Key pair: Naya key pair create karein aur download karein (.pem file).
   - Security group: HTTP (port 80), HTTPS (port 443), and SSH (port 22) ke liye rules add karein.
   - Instance ko launch karein.

2. **Connect to EC2 Instance**:
   - Terminal/CMD kholein.
   - SSH command run karein:
     ```sh
     ssh -i "path/to/your-key-pair.pem" ubuntu@your-ec2-public-ip
     ```

#### 3. Install Required Software
EC2 instance pe login hone ke baad, ye commands run karein:

1. **Update System**:
   ```sh
   sudo apt update && sudo apt upgrade -y
   ```

2. **Install Java (JDK)**:
   ```sh
   sudo apt install openjdk-17-jdk -y
   ```

3. **Install Maven**:
   ```sh
   sudo apt install maven -y
   ```

4. **Install Node.js and npm**:
   ```sh
   curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
   sudo apt install -y nodejs
   ```

5. **Install Git**:
   ```sh
   sudo apt install git -y
   ```

6. **Install Nginx**:
   ```sh
   sudo apt install nginx -y
   ```

#### 4. Clone Your Project from GitHub
1. **Clone the GitHub repository**:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

#### 5. Backend (Spring Boot) Setup and Run
1. **Navigate to backend directory**:
   ```sh
   cd springboot-backend
   ```

2. **Build the Spring Boot project**:
   ```sh
   mvn clean install
   ```

3. **Run the Spring Boot application**:
   ```sh
   mvn spring-boot:run
   ```

4. **Verify the Spring Boot application**:
   - Ensure the application is running on `http://localhost:8080` by default.

#### 6. Frontend (React) Setup and Run
1. **Navigate to frontend directory**:
   ```sh
   cd ../react-frontend
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Run the React application**:
   ```sh
   npm start
   ```

4. **Verify the React application**:
   - Ensure the application is running on `http://localhost:3000`.

#### 7. Configure Nginx as Reverse Proxy
1. **Edit Nginx configuration**:
   ```sh
   sudo nano /etc/nginx/sites-available/default
   ```

2. **Add the following configuration**:
   ```nginx
   server {
       listen 80;

       server_name your-ec2-public-ip;

       location / {
           proxy_pass http://localhost:3000;
           proxy_http_version 1.1;
           proxy_set_header Upgrade $http_upgrade;
           proxy_set_header Connection 'upgrade';
           proxy_set_header Host $host;
           proxy_cache_bypass $http_upgrade;
       }

       location /api {
           proxy_pass http://localhost:8080;
           proxy_http_version 1.1;
           proxy_set_header Upgrade $http_upgrade;
           proxy_set_header Connection 'upgrade';
           proxy_set_header Host $host;
           proxy_cache_bypass $http_upgrade;
       }
   }
   ```

3. **Restart Nginx**:
   ```sh
   sudo systemctl restart nginx
   ```

#### 8. Configure Security Groups
- Ensure that HTTP (port 80), HTTPS (port 443), and SSH (port 22) are open in your EC2 security groups.

#### 9. Access Your Application
- Open a web browser and navigate to `http://your-ec2-public-ip`.

#### 10. CI/CD Pipeline Setup (Jenkins)
1. **Install Jenkins**:
   ```sh
   sudo apt update
   sudo apt install openjdk-11-jdk -y
   curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee \
     /usr/share/keyrings/jenkins-keyring.asc > /dev/null
   echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
     https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
     /etc/apt/sources.list.d/jenkins.list > /dev/null
   sudo apt update
   sudo apt install jenkins -y
   sudo systemctl start jenkins
   sudo systemctl status jenkins
   ```

2. **Access Jenkins**:
   - Open a web browser and go to `http://your-ec2-public-ip:8080`.
   - Follow the setup wizard and install recommended plugins.

3. **Configure Jenkins Pipeline**:
   - Create a new Jenkins pipeline for your project.
   - Configure the pipeline script to build, test, and deploy your React and Spring Boot applications.

By following these steps, aap apne React aur Spring Boot project ko AWS pe deploy karke complete DevOps practice kar sakte hain. Har step pe ensure karein ki sab kuch properly configured hai aur koi error na aaye. Agar kisi step pe problem aaye, toh mujhe bataayein.
