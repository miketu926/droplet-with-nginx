# droplet-with-nginx

## Steps
* Create a droplet VM instance on Digital Ocean
  * an IP address is provided by the instance
  * add SSH key to Digital Ocean Account OR create password for this instance
  * SSH or use password to access the droplet instance created by using ip `ssh root@{ip}`
* Install nginx (server) - nginx.com/resources/wiki/start
  * sudo apt-get update
  * sudo apt-get install nginx
  * nginx -v to check installation
