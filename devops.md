

### Linux:
  - how to get a list of all running processes?
  - how to see how much disk space is available?
  - how to see all open filehandles on the local system?
  - how to watch the system calls a process is making?
  - how to find out if it's possible to open a tcp connection to a remote host on a specific port?
  - how to see if there's something listening on the local host at a specific port?
  - how to see all ports in use on the local machine?
  - how to see all mounted volumes?
  - how to mount a new volume?
  - how to setup key-based ssh authentication?
  - how to run a task every minute of every hour?
  - how to see if a file's contents have been changed?
  - how to see the max number of open files for a user?
    - how to change it?


### Chef:
  - what's the difference between a Berksfile and a Cheffile?
  - what happens when I run 'kitchen test -d never'?
  - make a chef cookbook to install nginx and add a virtual host to serve files from dir "/var/www/hello/"
  - how to test?
    - chefspec?
    - serverspec?
  - how to reference that cookbook in a project that requires nginx?


### Vagrant:
  - describe VagrantFile
  - describe what happens when I `vagrant up`


### Jenkins:
  - how to install Jenkins?
    - dependencies?
  - if I need to debug a failing job, where would I look for its files?
  - how to install a plugin?


### ElasticSearch, redis, RabbitMQ:
  - ever used it?
  - problems you've run into while administering, setting up, upgrading, etc?


### AWS:
  - describe the relationship between a VPC, security group, subnet, network interface, EC2 instance?
  - what's the difference between a region and an availability zone?
  - how does autoscaling work?
  - how would you make this?:
    - 1 load balancer
    - 2 web servers in autoscaling group (public-security-group)
      - ports 80, 443 publicly available
      - port 22 only accessible from whitelist of IP addresses
    - 2 worker servers
      - port 22 accessible only from whitelist of IP addresses
    - 1 database server (private-security-group)
      - network-accessible only from web server and worker subnets
    - elasticsearch server w/Kibana
  - how would you make another one just like it?


### Monitoring:
  - What are some common monitoring software options?
    - Which do you have experience with?
    - Which do you prefer?  Why?
    - How to install it?  How to configure it?

