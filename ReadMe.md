# Ansible role to install docker

Install latest stable docker / docker-compose package onto target host and add 'admin' user 
to the docker group

# Variables

see `defaults\main.yaml`

`docker_apt_arch` - docker repo architecture to install - default guesses based on ansible_arhitecture core variable
`docker_dir` - docker dir
`docker_compose_dir`: - docker compose dir