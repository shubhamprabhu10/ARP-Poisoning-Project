# ARP-Poisoning-Project
An ARP spoofing, also known as ARP poisoning, is a Man in the Middle (MitM) attack that allows attackers to intercept communication between network devices. The ARP spoofing attacker pretends to be on both sides of a network communication channel. The effects of ARP spoofing attacks can have serious implications for enterprises. The most direct impact of an ARP Poisoning attack is that traffic destined for one or more hosts on the local network will instead be steered to a destination of the attacker's choosing. Exactly what effect this will have depends on the specifics of the attack. The traffic could be sent to the attacker's machine or sent to a nonexistent location. In the first instance, there may be no observable effect, while the second may inhibit access to the network.
Once the attacker succeeds in an ARP spoofing attack, they can:
1. Continue routing the communications
2. Perform session hijacking
3. Alter communication
4. Denial of Service

The attack works as follows:
1. The attacker must have access to the network. They scan the network to determine the IP addresses of at least two devices.
2. The attacker uses a spoofing tool, to send out forged ARP responses. 
3. The forged responses advertise that the correct MAC address for both IP addresses, belonging to the router and workstation, is the attacker’s MAC address. This fools both router and workstation to connect to the attacker’s machine, instead of to each other.
4. The two devices update their ARP cache entries and from that point onwards, communicate with the attacker instead of directly with each other.
5. The attacker is now secretly in the middle of all communications.

Here are a few best practices that can help you prevent ARP Spoofing on your network:
1. Use a Virtual Private Network (VPN)⁠
2. Use static ARP
3. Use packet filtering
4. Run a spoofing attack
