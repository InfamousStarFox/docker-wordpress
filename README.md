# WordPress for Docker

Automagically pulls the latest docker [wordpress version](https://hub.docker.com/_/wordpress/) and skips the install prompts.

To be used for easy WordPress theme and plugin development

### Setup
[Install docker](https://www.docker.com/products/docker-desktop)

Clone the repository
```bash
git clone https://github.com/InfamousStarFox/docker-wordpress.git
cd docker-wordpress
```

### Run
With docker running, in terminal:
```bash
docker-compose up -d
```
Congrats! WordPress is now running at
http://localhost:8000

You can login with
- Username: admin
- Password: password

Docker will automatically create a `wp-content/` folder that you can directly access to place your themes and plugins in

### Stop
Done for the day? Stop the docker container with
```bash
docker-compose down
```
### Remove
Need to reset? Delete all the WordPress data and return to a fresh installation with 
```bash
docker-compose rm -fs
docker volume prune
```
