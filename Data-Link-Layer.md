<div align=center>
  <h1>Data Link Layer</h1>
</div>

## Data Link Layer

- The packets that we received from the Networking Layer are taken by the Data Link Layer.
- The data link layer is responsible for transporting the data packets to the physical layer.
- When a new device gets connected to a router, the router has a pool of IP Addresses. When a new device is recognized, that device first gets connected to a `DHCP server` and then there the device gets assigned a new IP Address.
- The devices connected in `LAN` communicate using the Data Link Layer Address.


### Situation

- Few computers are connected together in a `LAN` system.
- Let's say we have PC_a which wants to send some data to PC_b.
- Now it will check if PC_b has the Data Link Layer Address. If yes then it will send the data to PC_b.
- If the data was not found then PC_a will ask all the computers connected in the LAN.
- This is known as `ARP Cache`.
- ARP Cache is known as `Address Resolution Protocol Cache`.
- The data link layer address is actually the `MAC Address`.
- The device itself does not have a MAC Address but its components have their own MAC Address.

- The Data Link Layer processes the data in the form of `Frames`.
- A frame contains the data link layer address of the sender and the IP Address of destination.
- The data link layer works very closely with the physical layer.
- MAC Address is a 12 digit alphanumeric string and is unique.
- MAC Address means Media Access Control Address.
