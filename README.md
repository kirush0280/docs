# docs
Инструкции

 enable
 conf t
 interface vlan 1
 no ip dhcp-client enable
 ip address 192.168.1.20 255.255.0.0
 !
 exit
 write
 
 Для 10:
 copy tftp://192.168.1.111/4600-10.cfg startup.cfg
 copy tftp://192.168.1.111/3900_4600/4600_ven2XX_495.img nos.img
 

 Для 28:
 copy tftp://192.168.1.111/4600-28.cfg startup.cfg
 copy tftp://192.168.1.111/3900_4600/4600_ven3XX_495.img nos.img
 
 reload
 
