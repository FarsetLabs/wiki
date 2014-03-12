Switches
========

Core Switch (Linksys SRW2024)
-----------------------------

|Port|Assigned Use|VLAN|Notes|
|----|------------|----|-----|
|1|Co-work area Cisco Switch|*T|Trunk Port, LAG1 (LACP)|
|2|Co-work area Cisco Switch|*T|Trunk Port, LAG1 (LACP)|
|3|VoIP PoE Cisco Switch|*T|Trunk Port, LAG2 (LACP)|
|4|VoIP PoE Cisco Switch|*T|Trunk Port, LAG2 (LACP)|
|5|VoIP Server|5U||
|6|Unit1 Frontend Web Server|3T,5T,6T,7U||
|7|Iris (Wiki Server)|7U||
|8|CCTV DVR|6U||
|9|Management port|1U|Local management Port|
|10||||
|11|bloodbox Trunk|*T|Trunk Port|
|12||||
|13|WiFi AP1|*T|Trunk Port|
|14||||
|15||||
|16||||
|17||||
|18||||
|19|NAS (Synology Diskstation DS1511+)|3U|LAG6 (LACP)|
|20|NAS (Synology Diskstation DS1511+)|3U|LAG6 (LACP)|
|21||||
|22||||
|23||||
|24||||

Co-working Switch (Cisco Catalyst 2960)
---------------------------------------

|Port|Assigned Use|VLAN|Notes|
|----|------------|----|-----|
|1|Member Access Port|3U||
|2|Member Access Port|3U||
|3|Member Access Port|3U||
|4|Member Access Port|3U||
|5|Member Access Port|3U||
|6|Member Access Port|3U||
|7|Member Access Port|3U||
|8|Member Access Port|3U||
|9|Member Access Port|3U||
|10|Tibus|667U||
|11|VoIP Phone 1|5U||
|12|Member Access Port|3U|Print Server (RMSerene)|
|13|Member Access Port|3U|Lounge|
|14|Member Access Port|3U|Lounge|
|15|Member Access Port|3U||
|16|Member Access Port|3U||
|17|Member Access Port|3U||
|18|VoIP Phone 2|5U||
|19|Member Access Port|3U|Cabinet Corner|
|20|Member Access Port|3U|Cabinet Corner|
|21|Service Access Port|2U|Cabinet Corner|
|22|Member Access Port|3U|Event Space|
|23|Member Access Port|3U|Event Space|
|24|Network Bridge|3U|Event Space|
|G1|Core Switch Trunk|*T|Trunk Port, LAG1 (LACP)|
|G2|Core Switch Trunk|*T|Trunk Port, LAG1 (LACP)|

VoIP PoE Switch (Cisco SF302-08P)
---------------------------------

|Port|Assigned Use|VLAN|Notes|
|----|------------|----|-----|
|1||5U||
|2||5U||
|3||5U||
|4||5U||
|5||5U||
|6||5U||
|7||5U||
|8||5U||
|G1|Core Switch Trunk|*T|Trunk Port, LAG1 (LACP)|
|G2|Core Switch Trunk|*T|Trunk Port, LAG1 (LACP)|

Patch Panels
============

Panel 1
-------

|Ports|Location|
|-----|--------|
|01-10|Cowrk North/back wall|
|11-12|Reception wall|
|13-14|Lounge|
|15-16|Reception wall|
|17-21|Cowrk South/front wall|
|22-24|Event space|

Panel 2
-------

|Ports|Location|
|-----|--------|
|01-04|Workshop|

Panel 3 (Cat6 panel)
--------------------

|Ports|Location|
|-----|--------|
|01|Tibus line|
