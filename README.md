# agent-jenkins
docker run -d --network <network> --name agent_node -v /var/run/docker.sock:/var/run/docker.sock --init fredericeducentre/jenkins_agent_node -url http://<jenkins_container_name>:8080 <secret> <nom>
