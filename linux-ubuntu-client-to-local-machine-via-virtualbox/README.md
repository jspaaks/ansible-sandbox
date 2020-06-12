# Linux Ubuntu client to local machine via VirtualBox

Describe general layout of the approach

## prerequisites

- install virtualbox

## server side configuration

- ubuntu desktop 18.04 from iso (or make an appliance and put it on Zenodo)
- set vm's network port forwarding
- sudo apt install ssh-server

## client side configuration

- install ansible from PPA (mind the version)
- install openssh
- generate key pair
- copy key pair to server
- test ssh -i keyfile -p 2222 username@127.0.0.1|localhost
- test hello world playbook

