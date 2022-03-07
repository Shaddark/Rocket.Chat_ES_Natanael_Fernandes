# Rocket.Chat_ES_Natanael_Fernandes


I've done everything just as it is documentated on https://docs.rocket.chat/.
I've also used Amazon AWS EC2 server (free) to deploy the application.

Installation Process:

1- I created the "docker-compose.yml" file on my AWS EC2 server, and then started configuring it.
2- I configured the Firewall and the Fail2Ban ax explained on the docs.
3- I installed the docker and docker-compose in my AWS EC2 server.
4- Set up the hosts file.
5- Installed the Self-Signed SSL Certificate (no clue of why it is not working, sorry 😞).
6- Set up the permissions and configured NGINX.
7- Created the upstart job for MongoDB.
8- Rebooted and started up the application.

So the application is actually running on the following address: https://ec2-3-84-242-152.compute-1.amazonaws.com/
I also created a Admin user and a Test user, as it is shown below:
![image](https://user-images.githubusercontent.com/46090042/157108322-dc8de874-9c91-46b0-957d-86ba2d98a83d.png)

But, unfortunatelly, i couldn't access the API endpoint because it shows me this error:
![image](https://user-images.githubusercontent.com/46090042/157113022-01f25395-e662-4939-898d-e2e2a0f83a47.png)

Sorry for being late, i had a lot of work recently.

Anyways, i'm so thankful for the opportunity, and for the knowledge i've acquired with this test.
