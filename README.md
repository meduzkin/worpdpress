Description
Wordpress testing job for 2 month period.

The application should be launched at a click, with a minimum of interventions.
Deploying WordPress framework on the base from Centos, Apache, Redis and MariaDB.

Requirements
On your workstation should be installed:
Docker
Docker-compose

Install

In the main folder with the docker-compose.yml file, run the following commands:

$ docker-compose up

After it you can/should:
1. Open in your favourite browser http://124.0.0.76:80/
1.1. Enable WPSession plugin in WP ui.
2. Enjoy


Features
Unfortunately, it was not possible to completely solve the issue of storing PHP sessions in Redis, but you can:
1. To check up working, having passed under the link http://124.0.0.76:80/test.php (after that it is possible to see in the Redis the appeared record about session). (hostname "redis", password "redis_passwd")
2. Activate the plug-in (already downloaded to the project) allowing native WordPress to store the php session.
