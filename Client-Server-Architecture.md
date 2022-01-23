<div align=center>
  <h1>Client Server Architecture</h1>
</div>

## Client Server Architecture

- The Client-Server Architecture tells you about Servers, Connection between a client and the server and how it takes place.
- The client-server network is usually scaled large across countries and even continents.

## Servers

- Servers are the points where a client connects to have a connection for getting/providing a service, to do some task, etc.
- The servers have high upload speed because of what they need to do and their nature.
- The servers of big companies are distributed and they usually do not have only a single server.


## Client

- Client is us, who connects to the server for doing a task or for getting a service.
- Clients have high download speed (as compared to the upload speed).
- When `Client A` wants to connect to `Client B`, then this connection takes place only through the server, I.E.: Gaming.



# Peer to Peer Communication

- The devices gets connected to one another and there is no large server in this architecture.
- This can be scaled very rapidly and is a decentralized network.
- This network lets a device to communicate with other device(s) directly.
- Peer to peer networks are commonly small scale.
- Peer to peer networking can be more effective than client server networking because every computer on the network is given equal responsibility to communicate with each other.

# Devices

- These are some networking devices that we should atleast have an idea of, when learning networking and how a connection is established between devices and what happens in between.


## Repeater

- This device takes the network signal and sends it again in the desired direction before the signal becomes weak over the same network.
- These don't amplify the network but they regenerate the detected network with the same strength.

## Hub

- This is a multiport repeater.
- This cannot filter data and so the data is sent to all connected devices.
- The collision domain of all hosts through Hub remains one.
- There are two types of hub:
                        - Active Hub
                        - Passive Hub

### Active Hub

- This has its own power supply and can clean, boost and relay the given network.
- Used to extend maximum distance between two nodes.


### Passive Hub

- This takes power from the connected wires.
- This sends the network from the wire without clean and boosting the network.


## Bridge

- This operates at Data Link Layer.
- Filters content by reading MAC Addresses of source and destination of source and destination.


### Transparent Bridge

- In this the stations are completely unaware of the presence of bridge.


## Switch

- This is a multi port bridge with a buffer and a design that can boost efficiency.
- Large number of ports imply less traffic.
- A data link layer device.
- Error checking is done on the packets and only good packets are forwarded.

## Router

- This operates at Network layer.
- Connects LANs and WANs.
- This has a dynamic routing table.

## Gateway

- It is a passage to connect two networks together that may work upon different networking models.
- Messenger agents that take data from one system, interpret it and transfer it to another system.

## Brouter
- Bridge and router combined.
- This can work either at Networking Layer or at Data Link layer.
