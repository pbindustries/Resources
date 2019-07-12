# Docker resources and useful commands

## Maintainance/removal commands
- List all containers (only IDs) - `docker ps -aq`
- Stop all running containers - `docker stop $(docker ps -aq)`
- Remove all containers - `docker rm $(docker ps -aq)`
- Remove all images - `docker rmi $(docker images -q)`
- Remove all stopped containers, all dangling images, and all unused networks(-f to force it, --volumes to remove volumes too) - `docker system prune`
- 
