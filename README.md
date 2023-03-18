# Self-hosted cloud services
This repositoy contains ready to go cloud service for a self-hosted server (NextCloud for file storage, Jellyfin for video streaming...)

# Run
All the services and platforms runs under docker container and they are pulled from docker-hub dicrectly.
To run, use simply `docker compose` commands. 

As simple as:
```bash
sudo docker compose up -d
```

And let docker do the rest.

>__Note:__
>- `sudo docker compose ps` to get running docker images
>- `sudo docker compose stop` to stop all docker images
>- `sudo docker compose logs -F <imagename>` to get each image logs
