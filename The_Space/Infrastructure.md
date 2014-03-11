Contents
--------

-   [1 External Network](#External_Network)
-   [2 Internal Network](#Internal_Network)
    -   [2.1 IP Plan](#IP_Plan)
    -   [2.2 Static Leases](#Static_Leases)

External Network
================

Tibus Connection

||
|Network|89.185.154.120 255.255.255.248|
|Default Gateway|89.185.154.121|
|Usable IP addresses|89.185.154.122 - 89.185.154.126|
|DNS 1|212.108.64.5|
|DNS 2|89.185.144.36|

Current Allocations:

-   .122 : General Network ([Farbox](http://wiki.farsetlabs.org.uk/w/index.php?title=Farbox&action=edit&redlink=1 "Farbox (page does not exist)"))
-   .123 : Prototype Network
-   .124 : Reserved (And Monitored!)
-   .125 : Reserved (And Monitored!)
-   .126 : Reserved (And Monitored!)

Internal Network
================

IP Plan
-------

|Reserved Decade|Purpose|
|:--------------|:------|
|192.168.10.10-19|Core Network|
|192.168.10.20-29|Virtual Infrastructure/External Services|
|192.168.10.30-39|Storage|
|192.168.10.40-49|Media Services|
|192.168.10.50-59|CCTV/Alarm Services|
|192.168.10.150-250|DHCP (Served By [Farbox](http://wiki.farsetlabs.org.uk/w/index.php?title=Farbox&action=edit&redlink=1 "Farbox (page does not exist)"))|

Static Leases
-------------

|IP|Hostname|Services|
|:--|:-------|:-------|
|192.168.10.10|Farbox|Core Routing|
|192.168.10.20|fsl-eee7|BRB, SpaceAPI, Wiki, Redmine, SSH (ext:80,22)|
|192.168.10.21|kubrick|Mgmt (In development)|
|192.168.10.31-32|KitchenSync|Storage, BT|
|192.168.10.41|FES|Mythtv, Icecast|
|192.168.10.51|ipcam1|Camera (ext:8080)|
