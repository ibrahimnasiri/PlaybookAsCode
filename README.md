As computing infrastructure becomes 'hyperconvergedLinks to an external site.', incident response playbooks can be written for the CSIRT and for the computers they work with. In other words, a playbook can be interpreted by responders as well as server environments. Playbooks can be part of infrastructure as code.

Log into GitHub and access this GitHub ClassroomLinks to an external site..
GitHub will ask you to map your GitHub account to your identity in Canvas and will automatically fork the assignment repo into your user namespace
In your fork of the repo you will find a Cloudformation template, cloudformation.yaml, that defines a virtual machine web server and the network it runs in.
Clone your fork locally, and cut a new branch in your local clone. In that branch, modify cloudformation.yaml to do the following:
Add a security group that would isolate the web server from any communication within the VPC or with the public Internet.
Add incident response playbook steps that can be used to contain the web server for a scenario that requires isolation and investigation. Consider a use case/scenario like anomalous network activity detected through automated monitoring on the network. The steps should be written as comments in the Cloudformation source code. Make sure one of the containment steps shows how to update the security groups assigned to the web server for isolation.
Add a comment above the line that assigns security groups to the web server that would allow shell access from inside
Push your branch to your fork on GitHub and open a pull request to class upstream repo. Post the URL of your pull request to this Canvas assignment.
Hint: See the Cloudformation example documentation for Security GroupsLinks to an external site., in particular 'Remove the Default Rule'
