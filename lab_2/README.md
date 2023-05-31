## Цель
Настроить OSPF для Underlay сети

## IP PLAN

![](ip_plan.png)

## Статус настройки OSPF


<code>dc-sp-01# sh ip ospf neighbor 
Neighbor ID     Instance VRF      Pri State                  Dead Time   Address         Interface
3.3.3.1         1        default  1   FULL                   00:00:36    172.0.1.1       Ethernet1
3.3.3.2         1        default  1   FULL                   00:00:36    172.0.1.3       Ethernet2
3.3.3.3         1        default  1   FULL                   00:00:38    172.0.1.5       Ethernet3
3.3.3.4         1        default  1   FULL                   00:00:35    172.0.1.7       Ethernet4
</code>
