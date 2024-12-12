# ProjectOverview

The goal of this project is to create an end to end CI/CD pipeline that automates the process of code integration,testing for bugs and vulnerabilities using SonarCube,and deploying the code in Docker containers.The pipeline will be orchestrated through Jenkins, providing an efficient and streamlined workflow.

ProjectSteps:

1. Setting Up Jenkins for Automated Pipeline:
- Update the machine and install Java runtime environment.
- Allow port 8080 for Jenkins web access.
- Verify installation and access Jenkins webpage.
- Create a user,set up plugins,and create a pipeline for automated workflow.

2. Automated Triggering of Jenkins Pipeline from GitHub:
- Configure source code management in Jenkins with Git repository URL.
- Enable GitHub webhook trigger in Jenkins project settings.
- Verify webhook configuration by building the pipeline.
- Automate the process of pulling code from GitHub using webhooks.

3. Installation and Set up of SonarCube:
- Download and install Java17.
- Download and unzip SonarCube.
- Execute the sonar.sh script.
- Configure security group for SonarCube.
- Access SonarCube web interface.
- Set up a project in Sonar Cube using Jenkins.
-

4. Install and Configure SonarCube Scanner in Jenkins Pipeline:
- Copy project key from SonarCube for later use.
- Create a token in Sonar Cube with a 30-day expiry.
- Install SonarCube plugin and SSH plugin in Jenkins.
- Configure SonarCube scanner in Global Tool Configuration.
- Configure SonarCube server in Jenkins system settings.
- Add build step in Jenkins pipeline for SonarCube scanning.
- Paste the project key and SonarCube token.
- Save configurations and verify the SonarCube scan status.


5. Deploy Code on Docker:
- Install Docker on the EC2 instance.
- Configure Docker and update packages.


6. Executing Remote Commands on Docker Server:
- Configure Jenkins system with Docker server details.
- Run remote commands on Docker server.
- Create Dockerfile and copy contents to Docker server.


7. Deploying Code on Docker Container and Accessing it through a Browser:
- Create a Docker repository and move it to a remote server using SCP command.
- Configure Jenkins pipeline, build the code,and verify success.
- Fix permission denied error for running Docker commands.
- Build Docker image and run a container.
- Allow port 8085 for accessing the running container.
- Verify website functionality and address any CSS loading issues.

**Summary**:

Bycompletingthisproject,youwillhavedevelopedahands-onunderstandingofbuildingacomprehensiveCI/CDpipelineusingGitHub,Jenkins,SonarCube,andDocker.Thispipelinenotonlyenhancestheefficiencyofcodedevelopmentbutalsoensureshigh-qualitycodebyincorporatingautomatedtestingandsecuritychecks. 
