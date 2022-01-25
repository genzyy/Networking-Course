<div align=center>
  <h1>Transport Layer</h1>
</div>


## Transport Layer

- Let's say me and my friend are chatting on a messenger app. I send a message to my friend. This part of transferring that message from me to my friend is done by Networking Layer.
- Transport lies inside the device meaning transferring data inside a single device from the internet.
- The `Networking Layer` transfers data from one device to another.
- Transport Layer takes that data from Networking layer and sends it to the correct application.
- This layer is located on the end devices.

### Flowchart

- This flowchart gives a simple idea of what Transport Layer and Network Layer does and how

- ME => from Country A => Courier Service of A (X) => my parcel travelling from A to B done by someone (Y) => Courier Service of B => Country B => MY FRIEND.

- In the example, X is the Transport Layer and Y is the Network Layer.

### Multiplexer and Demultiplexer

- The transport layer multiplexer is located on the device from where the message/data is being sent and demultiplexer is on the device which receives the sent message.
- The transport layer is connected to the application using sockets and these sockets are running on port numbers.
- The transport layer also takes care of congestion like a lot of traffic on the same address or sending a lot of packets at once because of high upload speed that may cause data loss.
- Various congestion control algorithms are used for congestion control.
- Congestion control algorithms are built-in in TCP/IP.



### Checksum

- This is a random unique string attached to a packet when it is sent from one device to another. Every packet has different checksum string attached to it.
- When the packet is received on the end device the checksum is checked if they match or not. If not the packets are discarded or show error and if they match then its fine.


### Timers

- When a packet is sent in the connection to another device, it is only available on the connection for some time. This time is known as Timer. Once this runs out and the packet is not received on the end device, then it is discarded.

### Sequence Number

- This is another field which is used to identify the packets that are received on the end device.
- Sequence number is used on the device to align all the received packets in a sequence to not corrupt or destroy the received data on the end device.
