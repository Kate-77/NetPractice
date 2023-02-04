# NetPractice
## TCP/IP
TCP/IP stands for Transmission Control Protocol/Internet Protocol, which is the underlying communication language of the internet. It is a suite of protocols that govern how data is sent and received over a network.

In TCP/IP, every device on the network, such as a computer or smartphone, is assigned a unique IP address. An IP address is a series of numbers and dots that uniquely identifies a device on the network. There are two versions of IP addresses in use today: IPv4 and IPv6. IPv4 addresses are 32-bit numbers usually represented in "dotted decimal" notation, such as `192.168.1.1` IPv6 addresses are 128-bit numbers represented in hexadecimal notation, such as `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.

An IP address is divided into two parts: the **network address** and the **host address**. The network address identifies the network to which the device belongs, while the host address identifies the device within that network. This allows data to be sent to the right network and then directed to the right device within that network.

TCP and IP protocols work together to deliver data over the internet. IP is responsible for routing the data, while TCP is responsible for ensuring that the data is delivered to the correct application on the receiving device.

## Subnetting
Subnetting is a technique used to divide a larger network into smaller sub-networks or subnets. By doing this, it allows for better organization and control of the network, and it also improves the overall efficiency and security of the network.

When subnetting a network, an administrator will take the original IP address range of the network and divide it into smaller ranges of addresses called subnets. Each subnet will have its own unique network address and a range of host addresses. The network address of a subnet is used to identify the subnet, and the host addresses are used to identify the individual devices within the subnet.

To create subnets, an administrator will borrow bits from the host portion of the IP address and use them to create a subnet mask. The subnet mask is used to divide the IP address into a network address and a host address. The number of bits borrowed from the host portion of the IP address determines the number of subnets that can be created and the number of available host addresses in each subnet.

For example, an administrator might take a network that has an IP address range of `192.168.1.0``/24` This network has 24 bits assigned to the network address, leaving 8 bits for the host address. By borrowing some of those host bits to create a subnet mask, such as `255.255.255.128`, the administrator can create a subnet that has a network address of `192.168.1.0` and a range of host addresses from `192.168.1.1` to `192.168.1.127`. The administrator can then create additional subnets by borrowing more bits from the host address, such as `192.168.1.128``/25`, `192.168.1.192``/26` and so on.

The process of Subnetting allows for better organization, greater flexibility, and improved security. By dividing a network into smaller subnets, the administrator can assign specific IP address ranges to different departments, devices, and other elements of the network, which makes it easier to identify, manage, and secure those devices.

###Level 1
(https://github.com/Kate-77/NetPractice/blob/master/Level1/level1.png)
