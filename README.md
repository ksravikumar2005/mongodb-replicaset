# mongodb-replicaset
3 node mongodb replicaset
For the Impatient:

1. Clone this repo
2. Create a docker swarm with 3 nodes
3. Update the first node with the label: data1, the second with data2 and the third with data3
4. Run the command docker stack deploy -c swarm-compose-3-node.yml mongo-rep
5. Verify the services are running with docker service ls
