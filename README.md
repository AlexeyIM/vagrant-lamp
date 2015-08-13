Vagrant LAMP
==========

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)

This is a template for deploying a LAMP stack on a single Ubuntu Virtual Machine.
This template is leveraging [vagrant](https://www.vagrantup.com/) with
[ansible](http://www.ansible.com/home) provisioning.

## Requirements
* Ansible `>= 1.7`
* Vagrant `>= 1.7.3`

## Features
### System Stuff

- Ubuntu 15.04 (Vivid Vervet)
- Apache 2.4
- PHP 5.6
- MySQL 5.6
- cURL
- Composer
- Mcrypt
- Phpmyadmin

## Other Useful Stuff

- PHP Errors turned on
- Super easy database access and control
- PHP short tags turned on

## Get Started

* Install [Vagrant](https://www.vagrantup.com/)
* Install [Ansible](http://www.ansible.com/home)
* Clone current [GitHub Repository](https://github.com/AlexeyIM/vagrant-lamp)
* Run ``` vagrant up ```
* Access Your Project at [http://192.168.33.10/](http://192.168.33.10/)

## License

The MIT License (MIT). Please see [LICENSE](LICENSE) for more information.