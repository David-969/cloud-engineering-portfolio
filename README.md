Overview

This repository contains my hands-on cloud engineering projects, deployment workflows, troubleshooting notes, architecture diagrams, and infrastructure documentation.

The portfolio focuses on practical experience with:
  AWS EC2
  Linux administration
  Nginx web hosting
  Git and GitHub workflows
  SSH remote administration
  Cloud networking fundamentals
  Deployment troubleshooting

Portfolio Structure
Cloud-Engineering-Portfolio
diagrams
notes
projects
resume
screenshots


Featured Project
AWS EC2 Nginx Website Deployment

Built and deployed a static landing page on AWS EC2 using Linux and Nginx.

Skills Demonstrated
AWS EC2 administration
Linux command-line operations
Nginx configuration
SSH remote administration
GitHub deployment workflow
Security Group configuration
Troubleshooting and debugging
Deployment Architecture

Deployment Workflow
VS Code
↓
GitHub
↓
AWS EC2
↓
Nginx
↓
Live Website


Screenshots

First Deployment with SCP Without Git and Github.

![deploymentflow](Diagrams/deploymentflow.png)

Second Deployment with Git and Github

![Architecture Diagram](Diagrams/aws-ec2-nginx-architecture.png)

Third Deployment with Docker

![Docker-deploy-flow](Diagrams/Docker-deploy-flow.png)

EC2 Instance

![runningec2](Screenshots/runningec2.png)

Nginx Status

![runningnginx](Screenshots/runningnginx.png)

 Live Website
 
![Livewebsite](Screenshots/livewebsite.png)

 EC2 Instance
 
![securitygroups](Screenshots/securitygroups.png)

Github Repo

![githubpage](Screenshots/githubpage.png)

SSH Login Successful

![sshlogin](Screenshots/sshlogin.png)

inbound traffic allowed

![inbound-traffic-allowed](Screenshots/inbound-traffic-allowed.png)
Inbound traffic rule allowed here, makes it possible for the web page to display and be reachable.

inbound traffic Denied

![inbound-traffic-deny](Screenshots/inbound-traffic-deny.png)
Inbound traffic rule in deny state, stops the web page from being reachable.

page live inbound allow

![page-live-inbound-allow](Screenshots/page-live-inbound-allow.png)
This web page is live in this image because NACL inbound rule is allowed.

page unreachable inbound deny

![page-unreachabe-inbound-deny](Screenshots/page-unreachabe-inbound-deny.png)
This web page is unreachable due to NACL inbound rule in a deny state.

EC2 Monitoring

![EC2 Monitoring](Screenshots/ec2-monitoring.png)

Documentation
Projects

Detailed project documentation available in:

projects/aws-ec2-nginx-project.md
Technical Notes

Operational and troubleshooting notes available in:

notes/linux-commands.md

notes/nginx-notes.md

notes/ssh-troubleshooting.md

notes/aws-security-groups.md

notes/git-github-notes.md

notes/deployment-workflow.md
