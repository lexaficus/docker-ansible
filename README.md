docker-ansible
==============

Clean debian image built from the official debian image. Installs latest stable ansible using pip configured for local connection

- To install
    docker run --rm --name=docker-ansible itech/docker-ansible

- To test
    docker exec -it docker-ansible bash

Then you can play with ansible from command line:

    ansible -c local -m setup local
