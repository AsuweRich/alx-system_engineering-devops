# Web Infrastructure Design
This project contains tasks for learning more about the different ways a web infrastructure could be designed for web development.

## Tasks To Complete
  0. Simple web stack

  [0-simple_web_stack](https://github.com/AsuweRich/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/0-simple_web_stack) contains the URL of an image containing the design of a one server web infrastructure that hosts the website that is reachable via `www.foobar.com.` Start your explanation by having a user wanting to access your website.
    
  * Components to be used in the design:
      * 1 server.
      * 1 web server (Nginx).
      * 1 application server.
      * 1 application files (your code base).
      * 1 database (MySQL).
      * 1 domain name foobar.com configured with a www record that points to the server IP `8.8.8.8.`

  1. Distributed web infrastructure

  [1-distributed_web_infrastructure](https://github.com/AsuweRich/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/1-distributed_web_infrastructure) contains the URL of an image containing the design of a three server web infrastructure that hosts the website `www.foobar.com.`
    
  * Components to be added to the previous design:
      * 2 servers.
      * 1 web server (Nginx).
      * 1 application server.
      * 1 load-balancer (HAproxy).
      * 1 set of application files (your code base).
      * 1 database (MySQL).

  2. Secured and monitored web infrastructure

  [2-secured_and_monitored_web_infrastructure](https://github.com/AsuweRich/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/2-secured_and_monitorws_web_infrastructure) contains the URL of an image containing the design of a three server web infrastructure that hosts the website `www.foobar.com.` It must be secured, serve encrypted traffic, and be monitored.
    
  * Components to be added to the previous design:
      * 3 firewalls.
      * 1 SSL certificate to serve `www.foobar.com` over HTTPS.
      * 3 monitoring clients (data collector for Sumologic or other monitoring services).

  3. Scale up

  [3-scale_up](https://github.com/AsuweRich/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/3-scale_up) contains the URL of an image containing the design of a scaled up web infrastructure that hosts the website `www.foobar.com.`
    
  * Components to be added to the previous design:
      * 1 server.
      * 1 load-balancer (HAproxy) configured as cluster with the other one.
    - Split components (web server, application server, database) with their own server.
