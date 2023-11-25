## Initial Steps

Please follow the guidelines for setting up and starting this project.

### Necessary Preparations

This project requires the installation of ansible and functional ssh on your local computer. Additionally, ensure that you have two machines available for the target, both equipped with ssh capability.

* Installing ansible:

```sh
sudo apt-get install ansible
```

### Installation
1. Modify the IP addresses listed in the inventory file.

2. Execute the following command on your local computer: ```ansible-playbook playbooks/setup.yml```

3. After the playbook run successfully you should be able to see the working spring boot application on port ```8080``` of your ref03 machine.