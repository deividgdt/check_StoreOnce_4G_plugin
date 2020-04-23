# check_StoreOnce_4G_plugin
![](https://106c4.wpc.azureedge.net/80106C4/Gallery-Prod/cdn/2015-02-24/prod20161101-microsoft-windowsazure-gallery/hpe.hpestoreoncevsahpestoreoncevsa-3187.1.0.0/Screenshots/Screenshot1.png)

A Nagios/Centreon bash plugin for the 4G of StoreOnce. Simply bash code.

## Usage
+ `./check_storeonce4g_plugin -h <ip> -u <user> -p <pass> -o [<option> = serviceshealth || syshealth || compstatus ]`
  
  + `-h` IP address
  
  + `-u` Username
  
  + `-p` Password

  + `-o` Option
  
    + **serviceshealth**: service set information. Current status of: VTL,  Object Store,  Predupe, Catalyst RPC Server, SMM Thift RPC Service, NAS RPC Server, Replication, Buffer Manager, NAS, VTL RPC Server, Replication RPC Server, RepObj RPC Server, D2D Event Manager, NAS Share Manager, D2D Manager, D2D Reource Manager, ISCSI Daemon, Fiber Channel RPC Server, Store Manager Manager, Licensing RPC Server, RMC ERT iSCSI Daeon, NAS Buffer Manager, D2D Manager
    
    + **syshealth**: system health information. Current status of: Sysheal Status, Appliance Status, Data Services Status, Licence Status, Remote Support Status
    
    + **compstatus**: hardware components status: Current overall status. 
    
    
