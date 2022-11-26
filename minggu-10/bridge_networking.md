## Bridge Networking


### Step 1: The Basics
![list network](../images/10/networking_basics/listing_network.png)


### Step 2: Connect a container

``Create a new container by running docker run -dt ubuntu sleep infinity.``


![Create a new container](../images/10/bridge_networking/install-image-ubuntu.png)


``You can verify our example container is up by running docker ps.``


![container is up by running](../images/10/bridge_networking/ubuntu-network.png)


### Step 3: Test network connectivity

``Lets run a shell inside that ubuntu container, by running docker exec -it <CONTAINER ID> /bin/bash.``


![running docker exec](../images/10/bridge_networking/exec-container.png)


``Ping github``


![Ping github](../images/10/bridge_networking/ping-github.png)


### Step 4: Configure NAT for external connectivity

``Start a new container based off the official NGINX image by running docker run --name web1 -d -p 8088:80 nginx.``


![Container web1](../images/10/bridge_networking/create_new_container.png)


``You can connect from your Docker host using the curl 127.0.0.1:8088 command.``


![Docker host using the curl](../images/10/bridge_networking/curl.png)