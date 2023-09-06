**Task**: Configure Ansible server on VM 1 to deploy a webserver to VM2 and VM3 on port 8080 that displays the message: “Hello World from SJSU-X”, where X is 1 or 2 depending on which webserver.

**Steps done for implementation:**
 1. Deployed 3 ubuntu VMs on VMware Fusion.
 2. Installed ansible on one ubuntu VM that will behave as control node.
 3. Added ubuntu servers to the hosts file.
 4. Created an ssh key-pair on the control node and and configured those key pairs as authorized ssh pair in host VMs.
 5. Checked the connectivity.
 6. Created two playbooks: deploy-webserver.yml and undeploy-webserver.yml to deploy and undeploy the webservers.
