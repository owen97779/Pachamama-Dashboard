# Pachamama Cloud Dashboard

Powered by Homer, it is currently running in portainer. 

To update the site, make changes to **config.yml**. Push and the Github action will cause a Docker runner container, which shares a volume drive with the Homer container, to pull the new changes, (including assets 😊).