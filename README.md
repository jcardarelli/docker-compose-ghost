# docker-compose-ghost
Use `ghost-stack.yml` playbook to write template and run docker-compose file for a new Ghost deployment on Docker. 

## Setup
1. `cp example-vars.yml vars.yml`
1. Change variables in vars.yml to suit your project.

## Run Playbook
This will generate (and execute) the docker-compose.yml file.

`ansible-playbook ghost-stack.yml`
