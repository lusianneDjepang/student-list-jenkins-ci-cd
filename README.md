# Badge Status

[![Build Status](http://ec2-54-164-123-200.compute-1.amazonaws.com/buildStatus/icon?job=student-list)](http://ec2-54-164-123-200.compute-1.amazonaws.com/job/student-list/)

## Description

* This is a complete pipeline CI/CD with Jenkins to deploy a python application in production
* This infrastructure it's componed of 3 servers (gitlabserver, build server and production server)
* We use Ansible, Docker, Git and Gitlab tools
The differents stages are :
1. Ensure lint syntax of diferents langages (bash, yamel and markdown) is OK
2. Ensure servers are availables
3. Ensure syntax ansible is OK with ansible-lint
4. Build image on the build server and push artifact on the artifactory docker
5. Deploy application on the production server
6. Ensure application is deployed

by Lusianne DJEPANG (lusiannedjepang@gmail.com)
