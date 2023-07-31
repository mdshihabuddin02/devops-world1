# DevOps World
### Project Goal:
<p>This repo contains some of my DevOps projects. These projects are aimed at streamlining collaboration and deployment processes for better efficiency and productivity. They insist on automating many of the manual tasks involved in software development, testing, and deployment, making it easier to detect and fix issues quickly. The result is a faster, more agile development cycle that enables organizations to respond more quickly to changing market needs and customer demands.</p>

**Project List:**

* LMS is a JAVA Spring boot application built and deployed using the Jenkins pipeline.[See pipeline script from here](project-details1/spring-pipeline.md). This project has a DevSecOPS feature where I implemented hashicorp vault for credential management, trivy for vulnerability scan, AVScan, and ModSecurity. Every stage in the pipeline was executed using the Jenkins shared library.

* Local library Django project which was built and deployed as a pod to Kubernetes using Jenkins pipeline.
[See more](https://github.com/mdshihabuddin02/locallib-with-compose-and-kube/tree/br1).

* Jenkins shared library for reusable functionalities which reduces code boilerplates and the number of lines and also creates abstraction in the codebase.
[See more](https://github.com/mdshihabuddin02/jenkins-shared-lib1).

* All the configuration files for vagrant, ansible, terraform, and some docker-compose ymls.
[See more](https://github.com/mdshihabuddin02/config-list1/tree/br1).

* Ansible project for infrastructure provisioning and simple Python app deployment. [See more](https://github.com/mdshihabuddin02/deployment-using-ansible1/tree/branch1)