# keepalived
Sample Keepalived configuration with 3 nodes.
Each node has two network interfaces. eth0 -> VLAN100
                                      eth1 -> VLAN120
                                    
 VRRP ADV. packages sent periodically via eth0. VIPs listening on eth1. It is used with HAProxy for Kubernetes Loadbalancer on on-premise.
