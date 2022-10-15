# Contact-me

Contact-me is a chat application, demonstrating micro-service architecture.  
Composed of Angular frontend, spring backend, Eureka, RabbitMQ, and Zipkin,  
to enable communication with Slack servers and create a two way live chat.  
All set on docker containers and ready to run.  
  
To run Contact-me application, you need to have:  
1 - windows10 or newer.  
2 - docker-desktop installed and running - https://docs.docker.com/desktop/install/windows-install/  
2.1 - when NOT using docker-desktop, make sure your hosts file contains below lines to enable communication with backend:  
[put-your-docker-machine-ip-here] host.docker.internal  
[put-your-docker-machine-ip-here] gateway.docker.internal  
2.2 - to find your hosts file look at https://www.howtogeek.com/howto/27350/beginner-geek-how-to-edit-your-hosts-file/  
2.3 - to find your docker machine ip look at https://devilbox.readthedocs.io/en/latest/howto/docker-toolbox/find-docker-toolbox-ip-address.html  
3 - download docker-compose.yaml and .env files from this repository, to your computer.  
4 - open a command prompt (cmd) at docker-compose.yaml location.  
5 - run the command "docker-compose up -d".  
6 - open a browser to http://host.docker.internal:4200/, wait for web site to be available (about 5 minutes).  
7 - fill and send the contact form.  
8 - chat with me.  

this repository also contains config files for Contact-me application's spring cloud config server.  
