**Network Topology** - 

| **Name**      | **Domain** | **VLAN** | **Subnet**   | **Gateway** |
| ------------- | ---------- | -------- | ------------ | ----------- |
| Management    | N/A        | 1        | 10.0.1.0/24  | 10.0.1.1    |
| Corporate WAN | N/A        | 10       | 10.0.10.0/24 | 10.0.10.254 |
| Corporate LAN | atlas.lab  | 20       | 10.0.20.0/24 | 10.0.20.254 |
| Security      | atlas.lab  | 50       | 10.0.50.0/24 | 10.0.50.254 |
| Isolated LAN  | N/A        | 99       | 10.0.99.0/24 | 10.0.99.254 |
![[AtlasLabDiagram.drawio.png]]