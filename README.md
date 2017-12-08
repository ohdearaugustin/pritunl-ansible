# Skeleton for Ansible Roles

This is a skeleton for creating ansible roles according to [Ansible Playbooks Best Practices Directory Layout] (https://docs.ansible.com/ansible/latest/playbooks_best_practices.html#directory-layout).

Tasks:
- Task 1
- Task 2
- Task 3

This role supportes following remote hosts:
- ubuntu
- etc

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

You will need following software/roles to use it:
```
Ansible
Give examples
```

### Installing

Clone the skeleton into your ansible role folder.

```
git clone https://github.com/ohdearaugustin/ansible-role-skeleton
```

And modify it as you need it.

## Usage
If you want to apply this variables to a host group create a file `group_vars/your-group.yml` e.g. Replace `your-group` with the host group name which you created in the Ansible `hosts` file (do not confuse with /etc/hosts...).

### Role Variables
This paragraph will explain the used variables of the role. 
Following Variables are used by the Role:
```
example_var1: example1
example_var2: example2
```

Following represent the default values for specfic variables:
```
example_var1: default_value1
example_var2: default_value2
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

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
