# stack-wordpress
Stackspot :: Stack for WebSite development with Wordpress

Develop the components for your Wordpress website with our Stack. The stack prepares an environment with Docker containers for you to facilitate your development process. For this, the official images of Wordpress were used directly from Docker Hub, allowing you to choose which version best meets your needs.

The default template uses the [Wordpress:6.0.1](https://github.com/docker-library/wordpress/blob/193647657b9c00b68b63ba9ecf306c915764f8f5/latest/php7.4/apache/Dockerfile) image which already provides you with all the necessary libraries for installing a Wordpress instance.

The creation of a default database with [Mysql:5.7](https://github.com/docker-library/mysql/blob/eb9697a801186d440355c55e81512e0441a5a854/5.7/Dockerfile.oracle) and the mapping of plugin folders and Wordpress themes are also performed.