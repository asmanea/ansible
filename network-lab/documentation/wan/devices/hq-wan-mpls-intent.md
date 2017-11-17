## hq-wan-mpls

* LAN Interfaces

| interface     | description  | ip address   |
| ------------- | -------------| ------------ |
| GigabitEthernet3 | hq-core_ge0/2 |  172.20.0.1/30 |

* WAN Interfaces

| interface     | description  | ip address   | bandwidth |
| ------------- | -------------| ------------ |---------- |
| GigabitEthernet2 | mpls_provider_ge0/2 | 10.255.20.2/30 | 500.0 |

* Tunnel Interfaces

| interface     | profile      | ip address   | tunnel source |
| ------------- | -------------| ------------ | ------------- |
| Tunnel10 | dmvpn_mpls_1 | 172.16.101.1/24 | GigabitEthernet2 |

_________________________________________________________________

