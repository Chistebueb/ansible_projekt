## Getting Started

This guide will assist you in setting up and launching the project smoothly.

### Initial Setup

Before you begin, make sure your local computer is equipped with ansible and ssh functionality. You'll also need two target machines, both with ssh capabilities.

* **Install ansible:**

  Use the following command to install ansible on your system:

  ```sh
  sudo apt-get install ansible
  ```

### Installation
1. Locate the inventory file and replace the existing IP addresses with those of your target machines.

2. Execute the following command on your local computer: ```ansible-playbook playbooks/setup.yml```

3. Once the playbook execution is complete, check the functionality. You should be able to access the spring boot application on port 8080 of your ref03 machine.