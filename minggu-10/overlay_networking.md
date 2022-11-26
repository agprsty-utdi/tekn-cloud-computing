## Overlay Networking


### Step 1: The Basics

``Run a docker node ls to verify that both nodes are part of the Swarm.``

![Swarm](../images/10/overlay_networking/Swarm.png)

### Step 2: Create an overlay network

``Create a new overlay network called “overnet” by running docker network create -d overlay overnet.``


![docker network create](../images/10/overlay_networking/new_network.png)


### Step 3: Create a service

``Now that we have a Swarm initialized and an overlay network, it’s time to create a service that uses the network.``

![Create a service](../images/10/overlay_networking/services.png)


### Step 4: Test the network

![docker exec](../images/10/overlay_networking/exec.png)
![ping](../images/10/overlay_networking/ping.png)

