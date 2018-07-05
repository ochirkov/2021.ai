# Run ansible

`ansible-playbook jupyterhub.yml`

This role will be executed on local CentOS machine.
For remote execution ssh key should be specified and inventory file used.

# Run compose

`cd docker && docker build -t 2021ai .`

`docker-compose up -d` 

Above commands will create local docker image and compose will use it. 
