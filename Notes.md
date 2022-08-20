
# Hands-On Network Programming with C

Windows includes a utility, `tracert`, which lists the routers between your system and the destination system.

```shell
tracert example.com
```

When running `tracert`, some intermediate routers can be missing with the `Request timed out` message. This usually means that the system in question doesn't support the part of the __Internet Control Message Protocol__ (ICMP) protocol needed.

In Unix-based systems, the utility to trace routes is called `traceroute`.

One of IPv6's main advantages is that it has enough address space for every system to have its own unique publicly-routable address. The limited address space of IPv4 is largely mitigated by __network address translation__ (NAT) performed by routers.

