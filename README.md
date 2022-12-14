![UMEE_logo](https://github.com/the-node75/umee-tools/raw/main/umee-xsmall-logo%20.png)
# UMEE-tools
Our public usefull tools and services for UMEE network from [node75 & pro-nodes](https://www.mintscan.io/umee/validators/umeevaloper1vn5ysf7u9dssn2pm6h8agmqerxc5mq79p3e9ny) validator.

## Node monitoring tool

https://github.com/shurinov/mon_umee

Public community monitoring service: 
http://pro-nodes.com/mon/d/umee-1
### Metric connection settings
|Param | Value |
| :-:  | :-:|
Monitoring database name | umeemetricsdb
Monitoring server path (urls) | http://pro-nodes.com:8086
Monitoring server username | metrics
Monitoring server password | password

## Testnet Peggo and PFD overall dashboard

*Canon-2* testnet dashboard with peggo and pfd performance by validators.

Link: https://node75.org/mon/d/UMEE_Testnet_Peggo_PFD

## Mainnet Peggo and PFD overall dashboard

New version of overall dashboard. 

Allows you to monitor Peggo and price-oracle (Price-Feeder) status for each network validator.

Link to dashboard: https://node75.org/mon/d/UMEE_Main_Overall

![Mainnet Overall Dashboard screenshort 0](https://github.com/the-node75/umee-tools/raw/main/Umee_Mainnet_Overall_Dashboard_v1_0.png "Mainnet Overall dashboard screenshort 0")
![Mainnet Overall Dashboard screenshort 1](https://github.com/the-node75/umee-tools/raw/main/Umee_Mainnet_Overall_Dashboard_v1_1.png "Mainnet Overall dashboard screenshort 1")

## IBC relaying by out validator

|Chain 1 | Chain 2 | Status |
| :-:  | :-:|  :-:|
Umee (umee-1) "channel-9" | Gravity Bridge (gravity-bridge-3) channel-28 | <font color='green'>Active</font>
Umee (umee-1) "channel-22" | Crescent (crescent-1) "channel-6" | <font color='green'>Active</font>
Umee (umee-1) "channel-3" | Terra (columbus-5) "channel-26" | <font color='red'>Not active</font>
Umee (umee-1) "channel-20" | Evmos (evmos_9001-1 / evmos_9001-2) "channel-1" | <font color='red'>Frozen</font>


## RPC servers:
http://rpc-umee-0.node75.org:26657
Public RPC, P2P, Snapshot node 

## Seed node 
You can use this tenderseed server to get an up-to-date address book
```
86bd5cb6e762f673f1706e5889e039d5406b4b90@umee.seed.node75.org:10656
```
More info about [our seed node service](https://node75.org/?page_id=2974)

## Active validator in UMEE Testnets:

Canon-2 chain validator.

Link to explorer: https://explorer.network.umee.cc/canon-2/staking/umeevaloper1jpfl9lefcf9f8hk08k5v8nav6ukwvy6ed5c9ze
