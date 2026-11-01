# Portfolio Website Deployment

## Description
This Ansible role deploys a static portfolio website
using Nginx on Ubuntu Linux servers.

## Requirements
- Ubuntu EC2 instance
- Ansible installed
- SSH access to target server

## Features
- Installs Nginx
- Copies HTML and CSS files
- Configures Nginx
- Starts and enables Nginx service

## Usage

Run the following command:

ansible-playbook -i inventory.ini site.yml

## Website Pages
- Home
- About
- Projects
- Contact

## Web Server
Nginx
