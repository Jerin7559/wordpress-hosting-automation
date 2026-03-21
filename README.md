\# WordPress Hosting Automation using Ansible



This project automates the deployment of a WordPress website on a Linux server using Ansible.



\## Technologies Used

\- Ansible

\- Nginx

\- MariaDB / MySQL 10.6

\- PHP 8+

\- WordPress

\- phpMyAdmin

\- SFTP

\- Let's Encrypt SSL



\## Files

\- `site.yml` - main deployment playbook

\- `ssl.yml` - SSL setup playbook

\- `sftp.yml` - SFTP setup playbook

\- `ansible.cfg` - Ansible configuration

\- `inventory` - managed host details

\- `requirements.yml` - required Ansible collections



\## Features

\- User-based website root under `/home/username/websitename/public`

\- WordPress installation

\- phpMyAdmin access

\- Secure SFTP access

\- Free SSL certificate with HTTPS



\## Security Note

Sensitive credentials have been removed from this repository.

