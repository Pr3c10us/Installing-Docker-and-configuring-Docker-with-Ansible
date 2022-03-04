# Installing-Docker-and-configuring-Docker-with-Ansible

This Role combined with the playbook,can be used to Install Docker to a server host or multiple server hosts. It would also configure them to be able to run without root access by adding them to the Docker group.


If Ansible is installed on your pc or machine you can test the code on your machine by running 

$ ansible-playbook localhost -K installing_docker.yml
