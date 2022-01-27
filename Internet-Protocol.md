<div align=center>
  <h1>Internet Protocol</h1>
</div>


## IP

- This is known as `Internet Protocol`.
- The actual hopping of packets from one router to another happens over ISPs.
- These routers have a Networking Table where there are IP Addresses available to know which packet should be sent to what address.
- The IP Addresses are not actually the entire IP Address but some part of it is given there. For example, the IP Address of a device is `192.168.1.1`, so on the router's networking table there will be few blocks of this IP Address but not the entire address. This is known as `Subnetting`.
- In the IP Address `192.168.1.1`, the blocks `192.168.1` is the Subnet ID and `1` at the end is the host ID.
- Whenever a packet is forwarded by a router, it only has the subnet ID and not the host ID. The packet after reaching to the correct router, the router uses `DHCP` to send the packet to correct device.


## IPv4

- This is `32-bit` address.
- Using IPv4, we can make 2^32 IP Address.
- Ex. `192.168.1.1`.

## IPv6

- These are `128-bit` addresses.
- There can be 2^128 IPv6 Addresses => 3.4 * 10^38 IP Addresses.
- This IP Address is not backward compatible with IPv4, and IPv4 hosts and routers will not be able to deal directly with IPv6 traffic and vice-versa.

### Why everyone has not moved to IPv6 yet?

- Not having backward compatibility is one issue here.
- All ISPs need to shift to IPv6.
- Hardware should be made compatible for IPv6.


### IPv6 - More details about how its address is

- There are 8 numbers and every number is a hexadecimal number which is a 16 bit number.
- An IPv6 Address: `ABFE:F001:3210:9182:0000:0000:0001:0003`.
- We have the same subnet masking representation here as we did in IPv4.
- We can represent `0000` as `0` only or we can even leave that part empty like `...:1230::6549:...`.


## Classes of IP

- Class A => 0.0.0.0 - 127.255.255.255
- Class B => 128.0.0.0 - 191.255.255.255
- Class C => 192.0.0.0 - 223.255.255.255
- Class D => 224.0.0.0 - 239.255.255.255
- Class E => 240.0.0.0 - 255.255.255.255


## Subnet Mask

- It means the subnet mask will mask the given IP Address.
- In the IP Address, `192.168.1.1/24`, first 24 bits will be fixed, but all the bits after 24th but can change and are not fixed. By this we mean to hide the IP Address of all hosts that come into the range of `192.168.1.0` to `192.0.1.255`.
