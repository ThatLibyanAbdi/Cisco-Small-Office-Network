# Project Log

## Phase 1: Physical topology

Created a star topology using a Cisco 1941 router, a Cisco 2960-24TT switch and four PCs. Connected devices using copper straight-through Ethernet cables.

### Router interface troubleshooting

The router-to-switch link was initially down. Enabled GigabitEthernet0/0 using `no shutdown` in Cisco IOS and verified its up/up status using `show ip interface brief`. All physical links are now operational. IPv4 addressing and end-to-end connectivity testing remain pending.
