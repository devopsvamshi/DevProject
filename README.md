# DevProject
Testing some Ansible code to create the instance and deploy some application on it

We can create the instance in AWS by using AWS CLI, API and Open source automation tools like Ansible, Chef, Puppet and etc.

Here I have give the code to create an instance and deploy the application by using Anisble YML script.

I have written playbook to create a security group with respetcive ports, redirected iptable ports from http to https, created a new instance with the existing security group, deployed the wweb application and tested it by using curl and echo $?.

For your refrence:
There are several ways to redirect HTTP to HTTPS.
1. mod_rewrite 
2. page redirection 
3. HTML meta tag 
4. Port redirection using firewall (iptables,etc)

Here I have used iptables for port forwarding and establish respective connections.

