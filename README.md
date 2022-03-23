# docker-ngnix-reverse-proxy
NGINX Reverse Proxy set up in Docker
Using an NGINX reverse proxy in Docker gives you the ability to handle and manage web application requests to and from a containerized application in various ways.

### Usecase: 
This project is an example for testing and understand the NGNIX reverse proxy with Docker. In this test example we will try to run multiple containers with different web application stack namely Nodejs and PHP.

### Prerequisite: 
- Docker desktop

### Steps:
- docker-compose up
- Add hosts in your system host file /etc/hosts
-- 127.0.0.1	 dev.php.local
-- 127.0.0.1     dev.node.local

Once the cotainers are spun, you shoule be able to access PHP app from dev.php.local and Nodejs app from dev.node.local.
