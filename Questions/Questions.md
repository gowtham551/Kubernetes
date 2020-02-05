# Why kubernetes?
* using kubernetes we can able to create pods
* pods contain conntainers
* 1.maintain desired state
* 2.scalability
* 3.High availability

# what are 4 components in kubernetes?
* 1.Api server(decision maker)
* 2.controller(Helps to maintain desired state)
* 3.cluster(Maintain information like a memory)
* 4.scheduler(Assign work to nodes)

# why Replication Controller?
* 1.Desired state
* 2.creting multiple pods
* 3.deploy our application easily
* 4.cost is less

# disadvantages of ReplicationController?
* 1.Need to change labels manually
* 2.Resource wasting
* 3.Manually delete pods 

# what is pod?
* A pod is a basic unit of kubernetes. A pod consist of one or more container images

# Types of pods?
* single container pod(scp)
* multi container pod(mcp)

# where scp will use?
* it's widely used when a container runs on a physical machine on top of an operating system.

# where mcp will use?
* used for applications which are dependent on other applications/services for their functioning.