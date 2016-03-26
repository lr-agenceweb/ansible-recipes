## Ansible Recipes

This project contains a list of ansible recipes to install on every web server

### Requirements
Install [VirtualBox](https://www.virtualbox.org/)  
Install [Vagrant](https://www.vagrantup.com/)  
Install [Ansible](http://docs.ansible.com/ansible/intro_installation.html)  

### Usage
Clone it: `git clone git@github.com:lr-agenceweb/ansible-recipes.git`  
Go to the ansible folder: `cd ansible-recipes`  
Duplicate `vars/main.example.yml` into `vars/main.yml`  
Edit the configuration variables as you wish  
Load dependencies `(sudo) ansible-galaxy install -r requirements.yml`  
Run `ansible-playbook playbook.yml`  
That's it !  

### Contains
- **avconv**
- **htop**
- **unzip**
- **pydf**
- all recipes listed in Galaxy dependencies section

### Galaxy dependencies
- Git [![Git](https://img.shields.io/badge/galaxy-franklinkim.git-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/git)
- ZSH / oh-my-zsh [![ZSH / oh-my-zsh](https://img.shields.io/badge/galaxy-franklinkim.users--oh--my--zsh-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/users-oh-my-zsh)
- Nginx / Passenger [![Nginx / Passenger](https://img.shields.io/badge/galaxy-mtpereira.passenger-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/mtpereira/passenger)
- RVM / Ruby [![RVM / Ruby](https://img.shields.io/badge/galaxy-rvm_io.rvm1--ruby-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/rvm_io/rvm1-ruby)
- PHP CLI [![PHP CLI](https://img.shields.io/badge/galaxy-novuso.php--cli-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/novuso/php-cli/)
- PHP FPM [![PHP FPM](https://img.shields.io/badge/galaxy-nbz4live.php--fpm-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/nbz4live/php-fpm/)
- Composer [![Composer](https://img.shields.io/badge/galaxy-tersmitten.composer-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/tersmitten/composer/)
- MySQL [![MySQL](https://img.shields.io/badge/galaxy-mjanser.mysql-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/mjanser/mysql/)
- PhpMyAdmin [![PhpMyAdmin](https://img.shields.io/badge/galaxy-mjanser.phpmyadmin-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/mjanser/phpmyadmin/)
- NodeJS [![NodeJS](https://img.shields.io/badge/galaxy-williamyeh.nodejs-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/williamyeh/nodejs/)
- ImageMagick [![ImageMagick](https://img.shields.io/badge/galaxy-hashbangcode.imagemagick-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/hashbangcode/imagemagick/)
- Memcached [![Memcached](https://img.shields.io/badge/galaxy-geerlingguy.memcached-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/geerlingguy/memcached/)
- Htpasswd [![Htpasswd](https://img.shields.io/badge/galaxy-franklinkim.htpasswd-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/htpasswd/)
- Timezone [![Timezone](https://img.shields.io/badge/galaxy-franklinkim.timezone-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/timezone/)
- Environment [![Environment](https://img.shields.io/badge/galaxy-franklinkim.environment-5bbdbf.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/environment/)

### TODO
- ~~Nginx~~
- ~~Passenger~~
- ~~MySQL~~
- Let's Encrypt
- ~~PhpMyAdmin~~
- Backup gem
- ~~NVM~~
- ~~Node~~
- Backup Manager