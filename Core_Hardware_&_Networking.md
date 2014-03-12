The diagram for the local Farset Labs network can be viewed at the following link:

<http://www.evorack.com/farset/Farset-Network.pdf>

The local Network will be connected to the Evorack Cloud soon, and another diagram will follow.

Loosely speaking, the following people are "responsible" for the following areas of the network:
Routing, Firewalling, VPN: JT (Jonny)
Switches, WiFi APs: Dan Porter
VOIP: Conor Robinson
 **Of course, in keeping with the Hackerspace spirit, any member who feels competent enough to work on the network is, generally speaking, welcome to do so. Just please be respectful of equipment ownership rules and try and not break anything/compromise network security! :)**

VLANs
-----

In accordance with best security practises, the network in Unit 1 is segmented into separate VLANs, that have restricted access to/from each other and the Internet.

Glossary: Inbound means traffic originating *from elsewhere to VLAN in question*. Outbound means traffic originating *from VLAN in question to elsewhere*.

Guest - Outbound TCP ports 80 and 443 to Internet only. No inbound access. Connected to Farset-Guest WiFi
Members - Outbound to Internet, VOIP, Evorack Free VPSs and CCTV allowed. No inbound access. Connected to Farset-Members WiFi
CCTV - No Outbound allowed. Inbound allowed from outside.
DMZ - Nothing configured yet. Inbound ports allowed as and when required.
VOIP - Inbound from Internet VOIP ports allowed. Outbound to Sipgate allowed.

Equipment Ownership Under Loan to Farset
----------------------------------------

1 X pfSense Firewall/Router (Red Box) - ABPNI Computer Solutions Ltd (Loaned to Farset under the 60-day promise)
2 X ZyXel Managed Switches - Dan Porter (Loaned to Farset under the 60-day promise)
2 X Linksys Wireless APs - Dan Porter
1 X Asterisk Server - Conor Robinson (Hardware belongs to Farset, service built & run by Conor R)
