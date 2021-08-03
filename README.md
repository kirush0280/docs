# docs
Инструкции

 enable
 conf t
 interface vlan 1
 ip address 192.168.1.20 255.255.0.0
 !
 exit
 write
 copy tftp://192.168.1.111/4600-28.cfg startup.cfg
 copy tftp://192.168.1.111/4600-10.cfg startup.cfg
 copy tftp://192.168.1.111/3900_4600/S4600-XXP(-P)-SI-10.9.11-vendor_7.0.3.5(R0241.0453)_nos.img nos.img
 reload
 
