# Network-Network-Security-Bootcamp
Bootcamp Bitirme Projesi 
----------GİRİŞ-----------------

1. Ankara,İzmir,İstanbul routerlerının interface config işlemleri yapıldı.
2.İstanbul router'ına bağlı switchinde vlan 4 ve vlan 6 yaratıldı.
3.Bu vlan 4 'e IPV4 omurgasındaki serverlara bağlı olan fa0/1 ve fa0/2 bacakları , vlan 6 'ya IPV6 omurgasındaki serverlara bağlı olan fa0/3 ve fa0/4 bacakları eklendi.
4.İstanbul router'ındaki sub-intreface işlemleri yapıldı.
5.İstanbul routerından dış bacaklara yapılan ping testleri ile bağlantılar kontrol edildi.

 ---------OSPF--------
1.IPV4 omurgası için İstanbul routerına ospf komutları yazıldı.
2.Ankara routerına da yazılan ospf komutları  ile komşuluk kuruldu.
3.IPV6 omurgası için İstanbul routerına ospf komutları yazıldı.Router-id 1.1.1.1 şeklinde belirlendi.
4.İzmir routerına da ospf komutları yazıldı.Router id 3.3.3.3 olarak belirlendi ve komşuluk kuruldu.

-------STATIC ROUTING--------------
1.Routerlara komşuluk kurulacak network adresi yazılarak komşuluk kurulur.

------------ WEBACL-------------
1.DNS Serverların düzenlemeleri yapıldı ve DNS serverlara WEB Serverların adresleri eklendi.
2.End device lara DNS adresleri yazıldı.
3.Routerlara sadece udp 53 ve tcp 80 portlarından erişim olacak şekilde access-list komutları yazıldı.
