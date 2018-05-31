# php-nginx-in-docker
Using docker-compose to deploy PHP7 and Nginx in Docker.

## how to use

* for more detail about Nginx , plz view:  https://github.com/liumapp/docker-nginx-server

* vim /etc/hosts

	add content below :

		127.0.0.1 testa.com
		127.0.0.1 testb.com
		127.0.0.1 testc.com

* www contains php project and normal page . 

* running ``` docker-compose up -d ```

	and you can find :

	![1.jpg](https://github.com/liumapp/php-nginx-in-docker/blob/master/pic/1.jpg)