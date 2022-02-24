# Commands

For more details on the commands please look on the Orb Registry and Yaml Files

- [provision](provision.yml) - Provisions On Demand Runners by talking with AWS EC2
- [deprovision](deprovision.yml) - Deprovisions On Remand Runners by talking with AWS EC2
- [install-ansible](install-ansible.yml) - Install Ansible via Pip. Ansible is needed for On Demand Runners
- [install-dependencies](install-dependencies.yml) - Installs need Python Packages via Pip and Installs Ansible Modules from Ansible Galaxy
- [install-runner](install-runner.yml) - Installs and Configures the Runner agent on the On Demand Runners 