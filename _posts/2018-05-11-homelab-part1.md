---
layout: post
title: home lab part 1
date: 2018-05-11
category: homelab
---

I've been putting thought into my home network/lab setup recently and think its time to upgrade.
<!--more-->

Currently, the house is using an ISP provided modem/router/firewall for everything. Its a standard router with wifi and four LAN ports using a coaxial internet-side connection. For those four LAN ports, I have four devices that do not have wifi: desktop PC, Synology NAS, VMWare Server, and a remote access device. Since my primary desktop PC requires a physical LAN connection and is located in my first floor office, the router and all three of the other wired devices are in the office too. The rest of the house is wireless. Fire TV(s), Apple TV, Smart TV, Nintendo Wii U, the kid's MacMini, etc. 

I'd like to do four things with two more bonus objectives:
1. Relocate the headless devices to some other utility/closet space
2. Run wired connections to the compatible stationary devices 
3. Upgrade the wifi coverage of the entire house
4. Upgrade the firewall to a dedicated device
3. (bonus) - Create network segments (vLANs?) for the entertainment devices, phones, guest network, VMWare server, etc. 
4. (bonus) - Have a dope setup worthy of [/r/homelab](https://www.reddit.com/r/homelab/)

I'm not a network engineer (although I do know Jesse Fritz, which helps), but I've researched the hardware needed and I can pull cable... but how do you run wire between floors in a 25 year old house with a concrete slab foundation? Answer: A lot more work that I want to take on. I'll have to get creative and come through the one of the kid's second floor closets and possibly use the HVAC vertical drop voids, but I think it can be done.

### The Plan

Gear: I'm going to need a lot. In fact, the gear is what's going to drive the decision to break this project into phases. 

Location: The laundry/utility room in our house is centrally located on the first floor. There's plenty of space for networking/server gear in the adjacent void under the stairs, its climate controlled and the room has a door. The only and major downside is that its on the first floor without any exterior walls, making cable runs more difficult. Any other possibility involves putting the network rack and servers in a bedroom closet. The master closet could work. The drawback here is that its on the far side of the house away from most of the connections greatly increasing the length of cable runs. 

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

I hope to start get started next month. Until then.