<h2>Description</h2>
<p>Wordpress testing job for 2 month period.<br />The application should be launched at a click, with a minimum of interventions.<br />Deploying WordPress framework on the base from Centos, Apache, Redis and MariaDB.</p>
<h2>Requirements</h2>
<p>On your workstation should be installed:<br />Docker<br />Docker-compose</p>
<h2>Install</h2>
<p>In the main folder with the docker-compose.yml file, run the following commands:</p>
<p>$ docker-compose up</p>
<p>After it you can/should:<br />1. Open in your favourite browser http://124.0.0.76:80/<br />1.1. Enable WPSession plugin in WP ui.<br />2. Enjoy</p>
<h2><br />Features</h2>
<p>Unfortunately, it was not possible to completely solve the issue of storing PHP sessions in Redis, but you can:<br />1. To check up working, having passed under the link http://124.0.0.76:80/test.php (after that it is possible to see in the Redis the appeared record about session). (hostname "redis", password "redis_passwd")<br />2. Activate the plug-in (already downloaded to the project) allowing native WordPress to store the php session.</p>
