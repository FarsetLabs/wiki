Switches
========

Core Coworking Switch (Netgear GS748T)
-----------------------------

|Port|Assigned Use|VLAN|Notes|
|----|------------|----|-----|
|1|Core Router|*T|Trunk Port, LAG1 (LACP)|
|2|Core Router|*T|Trunk Port, LAG1 (LACP)|
|3|Event Space|*T|Trunk Port, LAG2 (LACP)|
|4|Event Space|*T|Trunk Port, LAG2 (LACP)|
|5|General Access Port|3U||
|6|General Access Port|3U||
|7|NAS (Synology Diskstation DS1815+)|3U|LAG9 (LACP)|
|8|NAS (Synology Diskstation DS1815+)|3U|LAG9 (LACP)|
|9|NAS (Synology Diskstation DS1815+)|3U|LAG9 (LACP)|
|10|NAS (Synology Diskstation DS1815+)|3U|LAG9 (LACP)|
|11|NAS (Synology Diskstation DS1511+)|3U|LAG10 (LACP)|
|12|NAS (Synology Diskstation DS1511+)|3U|LAG10 (LACP)|
|13|General Access Port|3U|SkyPi (Event Space info)|
|14|VM Server 5|7U,2T,3T,5T,6T,8T|Farset's VM Server|
|15|UniFi AP|2U,3T,5T,6T,7T|Coworking Space|
|16|General Access Port|3U||
|17|General Access Port|3U||
|18|General Access Port|3U||
|19|General Access Port|3U||
|20|General Access Port|3U||
|21|UniFi AP|2U,3T,5T,6T,7T|Project Space|
|22|General Access Port|3U||
|23|General Access Port|3U||
|24|General Access Port|3U||
|25|General Access Port|3U||
|26|General Access Port|3U||
|27|General Access Port|3U||
|28|General Access Port|3U||
|29|General Access Port|3U||
|30|General Access Port|3U||
|31|General Access Port|3U||
|32|General Access Port|3U||
|33|General Access Port|3U||
|34|General Access Port|3U||
|35|General Access Port|3U||
|36|General Access Port|3U||
|37|General Access Port|3U||
|38|General Access Port|3U||
|39|General Access Port|3U||
|40|General Access Port|3U||
|41|General Access Port|3U||
|42|VoIP Port|3U,5T|Reception Phone|
|43|Doorbot|7U,2T|Bolster's Pi Project|
|44|CCTV DVR|6U||
|45|Infrastructure Access Port|2U||
|46|General Access Port|3U||
|47|General Access Port|3U||
|48|UniFi AP|2U,3T,5T,6T,7T|Event Space|

Event Space Switch (Linksys SRW2024 v1.2)
---------------------------------

|Port|Assigned Use|VLAN|Notes|
|----|------------|----|-----|
|1|General Access Port|3U||
|2|General Access Port|3U||
|3|General Access Port|3U||
|4|General Access Port|3U||
|5|General Access Port|3U||
|6|General Access Port|3U||
|7|General Access Port|3U||
|8|General Access Port|3U||
|9|General Access Port|3U||
|10|General Access Port|3U||
|11|General Access Port|3U||
|12|General Access Port|3U||
|13|General Access Port|3U||
|14|General Access Port|3U||
|15|General Access Port|3U||
|16|General Access Port|3U||
|17|General Access Port|3U||
|18|General Access Port|3U||
|19|General Access Port|3U||
|20|General Access Port|3U||
|21|General Access Port|3U||
|22|General Access Port|3U||
|23|Core Switch Trunk|*T|Trunk Port, LAG1 (LACP)|
|24|Core Switch Trunk|*T|Trunk Port, LAG1 (LACP)|

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
|01|Tibus line (legacy)|
|07-10|Coworking extra ports|
