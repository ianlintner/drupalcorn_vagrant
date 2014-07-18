drupalcorn_vagrant
==================
This is a basic vagrant box created with puphpet for Drupal 7. It contains 
basic configuration for creating a Drupal 7 development website on a vagrant box.

This repo is provided as part of presentation on Vagrant for DrupalCorn 2014 in Iowa
http://prezi.com/pdxdmrovmmfa

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


Vagrant Performance
-------------------
Virtual Box Performance out of the box using shared folders can be pretty painful. 
Here are some links to information about speeding up VirtualBox Performance.

http://www.stefanwrobel.com/how-to-make-vagrant-performance-not-suck

http://chase-seibert.github.io/blog/2014/03/09/vagrant-cachefilesd.html
