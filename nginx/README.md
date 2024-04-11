# Ansible Role: Nginx

[NGINX](https://www.nginx.com/) is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers. It was originally written by [Igor Sysoev](http://sysoev.ru/en/).

**Official website**: https://nginx.org/<br>
**Official document URL**: https://nginx.org/en/docs/

## Require

This role only runs on Debian and its derivatives.

## Example Playbook

    ---

    - name: Install Nginx
    hosts: webservers
    roles: 
        - nginx
