# linux-nginx-node
Setting up a server from scratch. Linux>Nginx>Node
- [x] [Initial Server Setup with Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-20-04)
* Logging in as root
* Creating a New User
* Granting Administrative Privileges
* Setting Up a Firewall
* Enabling External Access for a Regular User
- [x] add landscape-sysinfo if missing on login
```
  sudo apt install landscape-common
  nano ~/.bashrc
  #add line to bottom of .bashrc
  landscape-sysinfo 
  ```

- [x] [Install Nginx on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-20-04)
* Installing Nginx
* Adjusting the Firewall to allow access to the service
* Managing the Nginx Process
* Setting Up Server Blocks
- [x] [Secure Nginx with Let's Encrypt on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-20-04)
* Installing Certbot
* Confirming Nginx’s Configuration
* Allowing HTTPS Through the Firewall
* Obtaining an SSL Certificate
* Verifying Certbot Auto-Renewal
- [ ] [Set Up a Node.js Application for Production on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-node-js-application-for-production-on-ubuntu-20-04)
* Install NVM
* Installing PM2 - process manager for Node.js applications
* Setting Up Nginx as a Reverse Proxy Server
