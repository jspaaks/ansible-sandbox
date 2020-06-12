This repository explains how to set up a server for running continuous integration tests on other hardware than what
GitHub provides. This can be useful when the code you want to test has special requirements, for example if

- it needs a GPU to run
- it needs multiple nodes
- the testing requires data that needs to stay on-premises for privacy reasons or legal reasons

This guide distinguishes between the _client_ and the _server_; the client is your own machine; the server is whichever
machine runs the tests. For either side, we'll explain what configuration needs to be done. For people who just want to
try out the instructions but don't have access to remote hardware, we included a few alternatives for running the server
locally as well, through the use of virtualization (with VirtualBox) and containerization (with Docker). 

For the client, we included instructions for Linux Ubuntu, Mac, and Windows; the server-side instructions all assume
Linux Ubuntu.

| client OS | server hardware | Link |
| --- | --- | --- |
| Linux Ubuntu | remote machine at SURF HPC Cloud | [link](linux-ubuntu-client-to-remote-machine-at-surf-hpc-cloud/README.md) |
| Linux Ubuntu | local machine via Docker         | [link](linux-ubuntu-client-to-local-machine-via-docker/README.md) |
| Linux Ubuntu | local machine via VirtualBox     | [link](linux-ubuntu-client-to-local-machine-via-virtualbox/README.md) |
| Mac          | remote machine at SURF HPC Cloud | - |
| Mac          | local machine via Docker | - |
| Mac          | local machine via VirtualBox | - |
| Windows      | remote machine at SURF HPC Cloud | - |
| Windows      | local machine via Docker | - |
| Windows      | local machine via VirtualBox | - |
