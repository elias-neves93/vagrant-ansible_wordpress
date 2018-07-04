# vagrant-ansible_wordpress
Wordpress with 2 machines provisioning with Vagrant (VirtualBox)

## Requirements
  - Vagrant >= 1.8
  - Ansible >= 2.5.5

### Deployment

After installed "Requirements" enter the project folder and run the following commands.
```sh
$ vagrant up
$ ansibleplaybook -i hosts provisioning.yml
```

## Access Wordpress for first Setup
Access browser IP Address
```sh
http://172.17.177.40
```

| Service | IP Address |
| ------ | ------ |
| Wordpress | 172.17.177.40 |
| MySQL | 172.17.177.42|
