- https://github.com/saminiir/level-ip 网络栈简单实现
	- Part 1, Ethernet & ARP: [http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp)
	- Part 2, IPv4 & ICMPv4: [http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4)
		- 对于icmp包，实现里面是直接解析处理过来的包，ping过来的包是怎么过来的呢？
	- Part 3, TCP Basics & Handshake: [http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
		- Only when the data is deemed intact, TCP can hand the data over to the application’s socket.
	- Part 4, TCP Data Flow & Socket API: [http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
	- Part 5, TCP Retransmission: [http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)
	- Why?
	  > Building a TCP stack(C, 500) -- Probably coded in the kernel, 
	  integrate the ethernet driver into the kernel. Add support for 
	  networking syscalls to kernel. (send, recv, bind, connect)
	  https://github.com/geohot/fromthetransistor