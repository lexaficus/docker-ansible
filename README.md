docker-ansible
==============

Based on https://github.com/iTech-Developer/docker-ansible

Clean debian image built from the official debian image. Installs latest stable ansible using pip configured for local connection

To quickly test it `docker run --rm -it --name=ansible lexaficus/ansible`

Check ansible version `docker run --rm lexaficus/ansible ansible --version`

Then you can play with ansible from command line:

    ansible -c local -m setup local
