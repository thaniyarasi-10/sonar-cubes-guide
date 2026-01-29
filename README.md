# sonar-cubes-guide

## Install the Sonar plugin in IntelliJ

1. Open IntelliJ IDEA
2. Go to File → Settings
3. In the left sidebar, click Plugins
4. Go to the Marketplace tab
5. Search for SonarQube for IDE
6. Click Install
7. Restart IntelliJ when it asks

## SonarQube Server (Local Setup)

### Install and Setup

- Go to  
  https://www.sonarsource.com/products/sonarqube/

- Download → **Community Build**  
  **Release 26.1.0.118079 (Download for free)**

- After download, extract all files.

- Go to:
  ```text
  sonarqube-26.1.0.118079/bin
- Open: 
  windows-x86-64
-Run:
  StartSonar.bat
- A Command Prompt opens and the SonarQube server starts.
- Open a browser and go to:
      http://localhost:9000
- Login using default credentials:
    Username: admin
    Password: admin
- Change password
- Create a new project and work on
  
