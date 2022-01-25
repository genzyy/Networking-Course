<div align=center>
  <h1>UDP</h1>
</div>

## UDP

- UDP stands for User Datagram Protocol.
- It is used to transport data from Network Layer to Transport Layer.
- Here data may or may not be delivered.
- Data loss can happen in this type of connection.
- A connectionless protocol.
- No connection is established between devices but still the data is sent to devices.
- UDP uses checksum if the data is corrupted or not but it will not do anything about it.
- UDP is faster as it is not checking if the data is received, not giving any feedback, etc.
- The command `tcpdump` should be looked at to know more about connections.

### UDP Packet

- These packets have source port number and destination port number attached to their header (2 bytes + 2 bytes).
- Length of the packet is known as Datagram and is also added to the packet header (2 bytes).
- Checksum is added to the header (2 bytes).
- Total size: 2^16 bytes.
- Header is of 8 bytes => port numbers, length of the packet, checksum.
- Size of the data = 2^16 - 8 bytes.


### Use Cases

- It is very fast.
- Video conferencing apps.
- DNS uses UDP.
- Gaming.
