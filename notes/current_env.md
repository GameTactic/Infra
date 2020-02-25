# Current Production Environment


## Servers

Running 3 VMs on 3 different hosts at Helsinki, Finland.
Each host is running Debian 10 Buster and are provisioned via CloudInit.
Each host has public IPv4 and IPv6. Hosts have installed only Docker
from official Docker repository. Docker is running in swarm mode.

### EU Node Stats

Each node has following resources running.

- CPU: 16 vCPU
- SSD: 75GB
- RAM: 20GB

### Versions

| Product       | Version       |
| ------------- | -------------:|
| Host OS       | Debian 10     |
| Docker        | 19.03.6       |
| Traefik       | 2.1.4         |
| MariaDB       | 10.2          |



### Stacks

- MariaDB Cluster, 6 Instances
- Redis Cluster, 3 Instances
- Traefik Loadbalancer, 1 Instance
- Gitlab Runner, 1 Instance
- Swarmpit, 4 Instances
- Echo, 1 Instance **Deprecated**
- Socket 1 Instance
- Auth, 3 Instances
- User, 1 Instance
- Room, 1 Instance
