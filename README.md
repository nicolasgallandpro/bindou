# bindou
The goal of this project is :
* root external trafic easily to multiple apps that are deployed in the same docker compose project, using Caddy server
* make thoses apps accessibles in the one page, via iframes and a right menu that allow to switch between them
  
## Installation
* create .bindou.env file using the template. 
* create a Caddyfile using the template
* to have a .env file with at least the variable COMPOSE_PRJECT_NAME set
