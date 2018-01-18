# Pritunl Ansible Role 
[![Build Status](https://travis-ci.org/ohdearaugustin/pritunl-ansible.svg?branch=master)](https://travis-ci.org/ohdearaugustin/pritunl-ansible)
This is a ansible role for installing a [Pritunl] (https://pritunl.com/) server.

Tasks:
- Task 1
- Task 2
- Task 3

This role supportes following remote hosts:
- ubuntu xenial

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

You will need following software/roles to use it:
```
Ansible
```

### Installing

Clone the skeleton into your ansible role folder.

```
git clone https://github.com/ohdearaugustin/pritunl-ansible
```

And modify it as you need it.

## Usage
If you want to apply this variables to a host group create a file `group_vars/your-group.yml` e.g. Replace `your-group` with the host group name which you created in the Ansible `hosts` file (do not confuse with /etc/hosts...).

### Role Variables
This paragraph will explain the used variables of the role. 
Following Variables are used by the Role:
```
default_soft_limit: 64000
default_hard_limit: 64000
root_soft_limit: 64000
root_hard_limit: 64000
pritunl_mongodb_host: "db.example.com"
pritunl_mongodb_port: 27017
pritunl_mongodb_name: "mypritunldb"
pritunl_log_path: "/var/log/mypritunl.log"
pritunl_static_cache: "true"
pritunl_bind_addr: "0.0.0.0"
pritunl_www_path: "/usr/share/pritunl/www"
pritunl_local_address_interface: "auto"
pritunl_port: 443
```

Following represent the default values for specfic variables:
```
default_soft_limit: 64000
default_hard_limit: 64000
root_soft_limit: 64000
root_hard_limit: 64000
pritunl_mongodb_host: "localhost"
pritunl_mongodb_port: 27017
pritunl_mongodb_name: "pritunl"
pritunl_log_path: "/var/log/pritunl.log"
pritunl_static_cache: "true"
pritunl_bind_addr: "0.0.0.0"
pritunl_www_path: "/usr/share/pritunl/www"
pritunl_local_address_interface: "auto"
pritunl_port: 443
```

These variables have to been, otherwise the role won't be functional.
```
example_var1: example1
example_var2: example2
```
## Built With

* [Ansible](https://www.ansible.com/) - The IT Automatation Tool used

## Contributing

Please read [CONTRIBUTING.md](https://github.com/) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Jonas Reindl** - *Initial work* - [ohdearaugustin](https://github.com/ohdearaugustin)

See also the list of [contributors](https://github.com/ohdearaugustin/pritunl-ansible/graphs/contributors) who participated in this project.

## License

This project is licensed under the BALA License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [Ignacio Sanchez Gines] (https://github.com/drhelius) wrote the [travis-ansible-demo] (https://github.com/drhelius/travis-ansible-demo) for the roles with ansible  
