<h2>Description</h2>
<p>Wordpress testing job for 2 month period.<br />The application should be launched at a click, with a minimum of interventions.<br />Deploying WordPress framework on the base from Centos, Apache, Redis and MariaDB.</p>
<h2>Requirements</h2>
<p>On your workstation should be installed:<br />Docker<br />Docker-compose</p>
<h2>Install</h2>
<p>In the main folder with the docker-compose.yml file, run the following commands:</p>
<p>$ docker-compose up</p>
<p>After it you can/should:<br />1. Open in your favourite browser http://124.0.0.76:80/<br />2. Enjoy</p>
<h2><br />Features</h2>
<p>PHP session are written in Redis now. Looks like all bugs were fixed.</p>
<p>To inspect PHP session:</p>
<p>1. Connect to Redis container;<br />
<p>2. Run "redis-cli -h redis", "AUTH redis_passwd";</p>
<p>3. Type "keys *" and let the magic begins. (But before it make some things in your site).</p>
