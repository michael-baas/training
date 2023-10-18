# NSE4

`Why is a static route needed?`

* If the destination IP isn’t in the routing table, the default route
allows a device to forward the request to another router. Without a
default route, if the route isn’t in a known network it can’t go
anywhere. If there are multiple static routes, the one with the lowest
administrative distance wins.
