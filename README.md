# DOCKER-BLOGHOSTER
After a lot of learning in Docker and Docker-compose and learned how to use it's container to host multiple services on them. I have developed a little project to help some web developers and some novices to setup there on Blogging Site on famous open source web hosting frameworks (All the database connection and port forwarding have been handled by me ;) , Just install Docker and run the Yaml file with 
Docker-compose. 
## GHOST
A powerful platform to share your content
Publish on your terms. You control the design, the content, the experience, and everything in between. No broken algorithms or social network rules. You're in charge.
## WORDPRESS
WordPress is a free and open-source content management system written in PHP and paired with a MySQL or MariaDB database. Features include a plugin architecture and a template system, referred to within WordPress as Themes.

PS: I will be trying to add multiple new CMS platforms in the repo and will be listening to your issues. 
## Setup
It is Fairly simple:
- Install Docker-ce on Your machine. ( I know you are capable to do it by searching on GOOGLE. Go ahead Install it.)
- Install Docker-compose
- Download the above yaml File and edit it to your Liking. (Don't change the name, it might give some warning or error on changing the name)
- Run the command with your terminal in the directory in which your yaml file is saved:     $docker-compose up$
- Voila! Your server is up and running. (The port numbers are given in the yaml file, take it as a reference)
- Happy  Blogging! 
