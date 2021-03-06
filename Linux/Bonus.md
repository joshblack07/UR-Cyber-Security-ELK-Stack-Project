## Bonus

The following are the specific commands the user will need. Some commands are written generally since the command would be dependent on specific information (username, IP, container name, etc.)

- `sudo docker ps` will display which containers are present and running.
- `sudo docker container start [container name]` will start the specified container. 
  - Example: `sudo docker container start relaxed kapitsa`
- `sudo docker container attach [container name]` will log the user into the specific container. 
  - Example: `sudo docker container start relaxed kapitsa`
- `ssh username@IP` will log a user into a new machine as long as it is running and allowing access. 
  - Example: `ssh sysadmin@10.2.0.4`
- `ansible-playbook [playbook name].yml` will run the playbook. 
  - Example: `ansible-playbook ELK-server.yml`
- `curl https://gist.githubusercontent.com/slape/5cc350109583af6cbe577bbcc0710c93/raw/eca603b72586fbe148c11f9c87bf96a63cb25760/Filebeat >> /etc/ansible/filebeat-config.yml` will pull the Filebeat config file from the specified website.
- the `nano` command was used to add/edit configuration files, playbooks, hosts, etc. 
  - Example: `nano ELK-server.yml`
