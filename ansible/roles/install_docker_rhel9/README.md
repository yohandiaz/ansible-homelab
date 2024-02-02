Role Name
=========

Installing docker in rhel9.

Requirements
------------

Role Variables
--------------

Docker repository
docker_repo: "https://download.docker.com/linux/centos/docker-ce.repo"

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - name: Install docker on RHEL
      hosts: docker_servers
      become: yes
      roles:
        - install_docker
