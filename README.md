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
