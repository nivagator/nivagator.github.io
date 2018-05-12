---
layout: post
title: home lab
date: 2018-05-11
category: homelab
---

I've been putting thought into my home network/lab setup recently and think its time to upgrade.

Currently, the house is using an ISP provided modem/router/firewall for everything. Its an all in one unit with wifi and four LAN ports with a coaxial internet-side connection. I have four devices that do not have wifi: desktop PC, Synology NAS, VMWare Server, and a remote access device. Since my primary desktop PC requires a physical LAN connection and is located in my first floor office, the router - and all three of the other wired devices - is in thats same room. The rest of the house is wireless. Fire TV(s), Apple TV, Smart TV, Nintendo Wii U, the kid's MacMini, etc. 

Initially, I'd like to accomplish four things with two more bonus objectives:
1. Relocate the headless devices to another, utility/closet space
2. Run wired connections to the compatible stationary devices 
3. Upgrade the wifi coverage of the entire house
4. Upgrade the firewall to a dedicated device
3. (bonus) - Create network segments (vLANs?) for the entertainment devices, phones, guest network, VMWare server, etc. 
4. (bonus) - Have a dope setup worthy of [/r/homelab](https://www.reddit.com/r/homelab/)

I'm not a network engineer (although I do know Jesse Fritz, which helps), but I've researched the hardware needed and I can pull cable... but how do you run wire between floors in a 25 year old house with a concrete slab foundation? Answer: A lot more work that I want to take on. Or... maybe you follow the vertical HVAC drops and other intentional voids already present in the house. I'm not 100% sure it can be done, but based on what I know about what's behind the walls of my house, I think its possible. 

### The Plan

Gear: I'm going to need a lot. In fact, the gear is what's going to drive the decision to break this project into phases. With that, lets outline the phases. The laundry/utility room in our house is centrally located under the stairs on the first floor. There's plenty of space for networking/server gear in the voids under the stairs, its climate controlled, its secluded and closed off by a door. This is the most ideal location for my network closet with its primary drawback of being on the first floor... and under the stairs.

#### Phase I
1. Run Cat6 ethernet drops to the living room(4), office(2-4), game room(4) and master bedroom(2-4)
2. Terminate these drops in the laundry room
3. Acquire and install a managed network switch with 16+ ports, 24 port patch panel and a 12u wall mounted network rack
4. Continue to use the ISP provided device as the modem, wifi router and firewall
5. Relocate the headless devices to the utility room and/or the network rack

#### Phase II
1. Upgrade the wifi to a more robust/secure device
2. Upgrade to a dedicated firewall device
3. Install UPS

I hope to start phase I next month. Until then.