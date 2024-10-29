# OrangeHRM PROD Image - PHP 7.4
[![Docker Automated](https://img.shields.io/docker/automated/orangehrm/orangehrm-environment-images.svg)](https://hub.docker.com/r/orangehrm/orangehrm-environment-images/) [![Docker Pulls](https://img.shields.io/docker/pulls/orangehrm/orangehrm-environment-images.svg)](https://hub.docker.com/r/orangehrm/orangehrm-environment-images/) [![Docker Status](https://img.shields.io/docker/build/orangehrm/orangehrm-environment-images.svg)](https://hub.docker.com/r/orangehrm/orangehrm-environment-images/) [![Build Status](https://travis-ci.org/orangehrm/orangehrm-prod-environment.svg?branch=php-7.2)](https://travis-ci.org/orangehrm/orangehrm-prod-environment)

## Introduction

This repository contains the prod 7.4 (PHP 7.4 production) image which is used by the OrangeHRM PROD Environment. Prod 7.4 image has been extended from the rhel8 image. 

All the added configurations and installed modules are crucial to the OrangeHRM application. And the image will only listen to the 443 port by default.

## How to use ?

1. get a docker pull - `docker pull orangehrm/orangehrm-environment-images:prod-php-latest-rhel-8` 
2. run the image - `docker run -itd --name <NAME> -p 443:443 orangehrm/orangehrm-environment-images:prod-php-latest-rhel-8`