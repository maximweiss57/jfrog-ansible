this is my first automation project using ansible,
this repository contains the following files:
- kubernetes manifests for Jfrog artifactory deployment
- kubernetes manifests for Flask application deployment
- two global manifests to configure evironment: 
    - cluster configuration maninfest
    - metalLB 
- ansible playbook to prepare the environment and deploy jfrog artifactory and flask application