# ansible-bosh-jumpbox

### Description

This is Ansible Playbook that contains all needed software to manage BOSH and CF. This proejct serves the same goals as [jumpbox-boshrelease](https://github.com/cloudfoundry-community/jumpbox-boshrelease), but instead of `bosh-init` it uses Ansible as a deployment tool. Using `bosh-init` is fine too, still there are some limitations

1. managing and customization of Ansible project is much more easier;
1. you don't need recreate an instance after configuration updating;
1. Ansible makes it possible to run this scripts on a PaaS of your choice, which is useful for development purposes;



