docker-ansible
==============

Clean debian image built from the official debian image. Installs latest stable ansible using pip configured for local connection

To quickly test it `docker run --rm -it --name=docker-ansible itech/docker-ansible`

Then you can play with ansible from command line:

    ansible -c local -m setup local
