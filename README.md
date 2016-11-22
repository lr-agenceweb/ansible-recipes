## Ansible Recipes

This project contains a list of ansible recipes to install on every web server (only tested with Ubuntu 14.04 Trusty)

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

### PHPMyAdmin vs Adminer
Both are included in recipes but by default, only Adminer is activated.  
If you want to switch back to PHPMyAdmin instead, change the `install_phpmyadmin` boolean to `true` and `install_adminer` to `false`


### Tools

 Technology | Description
----------- | -----------
**avconv** | Audio and video converter
**htop** | Monitorize VPS processes
**unzip** | Usnzip files
**pydf** | Show informations about VPS disk space
**wkhtmltopdf** | Convert HTML code to PDF file
**Git** [![Git](https://img.shields.io/badge/galaxy-franklinkim.git-660198.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/git) | Use git tools
**ZSH / oh-my-zsh** [![ZSH / oh-my-zsh](https://img.shields.io/badge/galaxy-franklinkim.users--oh--my--zsh-660198.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/users-oh-my-zsh) | Shell replacement
**Nginx** [![Nginx](https://img.shields.io/badge/galaxy-geerlingguy.nginx-660198.svg?style=flat-square)](https://galaxy.ansible.com/geerlingguy/nginx/) | Installation of web server (Rails friendly)
**RVM / Ruby** [![RVM / Ruby](https://img.shields.io/badge/galaxy-rvm_io.ruby-660198.svg?style=flat-square)](https://galaxy.ansible.com/rvm_io/ruby) | Installation of Ruby version through RVM
**PHP FPM** [![PHP FPM](https://img.shields.io/badge/galaxy-zerohacks.php5--fpm-660198.svg?style=flat-square)](https://galaxy.ansible.com/zerohacks/php5-fpm/) | PHP compiled for Nginx
**Composer** [![Composer](https://img.shields.io/badge/galaxy-tersmitten.composer-660198.svg?style=flat-square)](https://galaxy.ansible.com/tersmitten/composer/) | Dependency Management for PHP
**MariaDB** [![MariaDB](https://img.shields.io/badge/galaxy-mjanser.mysql-660198.svg?style=flat-square)](https://galaxy.ansible.com/mjanser/mysql/) | Database management system
**Redis** [![Redis](https://img.shields.io/badge/galaxy-geerlingguy.redis-660198.svg?style=flat-square)](https://galaxy.ansible.com/geerlingguy.redis/) | Database and cache management
**PhpMyAdmin** [![PhpMyAdmin](https://img.shields.io/badge/galaxy-mjanser.phpmyadmin-660198.svg?style=flat-square)](https://galaxy.ansible.com/mjanser/phpmyadmin/) | Handle the administration of MySQL databases
**Adminer** [![Adminer](https://img.shields.io/badge/galaxy-geerlingguy.adminer-660198.svg?style=flat-square)](https://galaxy.ansible.com/geerlingguy/adminer/) | Handle the administration of MySQL, PostgreSQL, SQLite, ... databases
**NodeJS** [![NodeJS](https://img.shields.io/badge/galaxy-williamyeh.nodejs-660198.svg?style=flat-square)](https://galaxy.ansible.com/williamyeh/nodejs/) | Include npm to manage node modules
**Postfix** [![Postfix](https://img.shields.io/badge/galaxy-Stouts.postfix-660198.svg?style=flat-square)](https://galaxy.ansible.com/Stouts/postfix/) | Email server to send emails
**ImageMagick** [![ImageMagick](https://img.shields.io/badge/galaxy-hashbangcode.imagemagick-660198.svg?style=flat-square)](https://galaxy.ansible.com/hashbangcode/imagemagick/) | Image converter
**Memcached** [![Memcached](https://img.shields.io/badge/galaxy-geerlingguy.memcached-660198.svg?style=flat-square)](https://galaxy.ansible.com/geerlingguy/memcached/) | Cache manager
**Htpasswd** [![Htpasswd](https://img.shields.io/badge/galaxy-franklinkim.htpasswd-660198.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/htpasswd/) | Apache htpassword for Nginx
**UFW** [![UFW](https://img.shields.io/badge/galaxy-franklinkim.ufw-660198.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/ufw/) | Firewall
**Fail2Ban** [![Fail2Ban](https://img.shields.io/badge/galaxy-franklinkim.fail2ban-660198.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/fail2ban/) | Ban user by behavior
**ProFTPD** | Add some rules to securize FTP transfer
**Backup Manager** [![Backup Manager](https://img.shields.io/badge/github-lr--agenceweb.backup--manager-F9690E.svg?style=flat-square)](https://github.com/lr-agenceweb/ansible-backup-manager) | Backup folders and export it to FTP
**Timezone** [![Timezone](https://img.shields.io/badge/galaxy-franklinkim.timezone-660198.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/timezone/) | Configure correct timezone to VPS
**Environment** [![Environment](https://img.shields.io/badge/galaxy-franklinkim.environment-660198.svg?style=flat-square)](https://galaxy.ansible.com/franklinkim/environment/) | Set correct locales for VPS


### TODO
- Let's Encrypt
- Backup gem (database export)
