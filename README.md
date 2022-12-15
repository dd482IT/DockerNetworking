# Docker Networking
## Basics
 Commands:
 
 docker network create <name> 
 
 sudo docker network ls

## Network Types 
1. Bridged Network: The default network for docker is bridged Network.
This requires you to expose the port on the container and connect it to a host port. 
This creates interfaces for each container and has a default gateway and subnet IP space. Any containers within the network will be able to communicate and get IP addresses from the Docker DHCP server. You cannot isolate containers from each other and only refer to containers by IP, no name resolution.
2. Cutom Bridged Network:  
3. Host Network:
4. None Network:
