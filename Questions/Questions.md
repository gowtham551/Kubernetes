# Why kubernetes?
* 1.maintain desired state
* 2.scalability
* 3.High availability

# why Replication Controller?
* 1.Desired state
  2. creting multiple pods
  3. deploy our application easily
  4. cost is less

# disadvantages of ReplicationController?
* 1.Need to change labels manually
  2. Resource wasting
  3. Manually delete pods 

# what is pod?
* A pod is a basic unit of kubernetes. A pod consist of one or more container images

# Types of pods?
* single container pod(scp)
* multi container pod(mcp)

# where scp will use?
* it's widely used when a container runs on a physical machine on top of an operating system.

# where mcp will use?
* used for applications which are dependent on other applications/services for their functioning.