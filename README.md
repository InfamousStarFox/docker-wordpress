# WordPress for Docker

Automagically pulls the latest docker [wordpress version](https://hub.docker.com/_/wordpress/) and skips the install prompts.

To be used for easy WordPress theme and plugin development

```bash
# Start the docker container
docker-compose up -d

# Stop the docker container
docker-compose down

# Delete all container data container
docker-compose rm -fs
```

Defaults
- Username: admin
- Password: password
