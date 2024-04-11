# Ansible Role: Apache

The [Apache HTTP Server]() Project is a collaborative software development effort aimed at creating a robust, commercial-grade, featureful, and freely-available source code implementation of an HTTP (Web) server. The project is jointly managed by a group of volunteers located around the world, using the Internet and the Web to communicate, plan, and develop the server and its related documentation. This project is part of the Apache Software Foundation. In addition, hundreds of users have contributed ideas, code, and documentation to the project.



**Official website**: https://apache.org//<br>
**Official document URL**: https://httpd.apache.org/docs/

## Require

This role only runs on Debian and its derivatives.

## Example Playbook

    ---

    - name: Install Apache2
    hosts: webservers
    roles:
        - apache2         
