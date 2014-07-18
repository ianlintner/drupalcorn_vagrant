drupalcorn_vagrant
==================
This is a basic vagrant box created with puphpet for Drupal 7. It contains 
basic configuration for creating a Drupal 7 development website on a vagrant box.

Instructions
------------
* clone repo
* vagrant up
* update hosts file with the following entries
* 192.168.56.101 drupal.dev
* 192.168.56.101 www.drupal.dev
* Navigate to http://drupal.dev in your browser
* MySql Config
* host: localhost
* Username: drupal
* Password: drupal
* Database: drupal

SSH Into the box using: vagrant ssh

MySql Root Password is: vagrant
