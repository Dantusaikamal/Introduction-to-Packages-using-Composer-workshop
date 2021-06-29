# Packaging using Composer workshop

This repository contains my notes and references for my workshop on Packaging Ecosystems and Dependency Managers.

![Alt Text](https://github.com/Dantusaikamal/Packaging-using-Composer-workshop/blob/main/composer-big.png)

Checkout:
1. https://packagist.org/
2. https://packagist.org/packages/moodle/moodle
3. https://getcomposer.org/


In Order to install Moodle package, follow: 
https://fsmi.wiki/index.php/User:Ranjithraj/installers/moodle


Installation of Composer in Debian:

$sudo apt update

$sudo apt install wget php-cli php-zip unzip

$wget -O composer-setup.php https://getcomposer.org/installer

$sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer

Run `composer` to check if it is installed properly.
