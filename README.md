# deploy_simple_wp_mysql_swarm
Simple deploy wordpress and mysql on docker swarm

You need:
1. Docker Swarm install
2. Create or download docker-compose.yml from this repo
3. Start command on master-node:
       docker stack deploy --compose-file docker-compose.yml name-stack
4. Check work
       docker stack ls
