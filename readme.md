this is my first automation project using ansible,
this repository contains the following files:
- kubernetes manifests for Jfrog artifactory deployment (jfrog-yamls directory)
- kubernetes manifests for Flask application deployment (flask-yamls directory)
- two global manifests to configure evironment: 
    - cluster configuration maninfest (cluster-config.yaml)
    - metalLB (metalLB.yaml)
- ansible playbook to prepare the environment and deploy jfrog artifactory and flask application (setup.yaml)

in order to run the playbook, you need to have the following:
- ansible installed on your machine (control node)
- target node with established ssh connection and sudo privileges