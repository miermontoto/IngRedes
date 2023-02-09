## General
show active / show vlan
ena → config

## Establecer VLAN
vlan <num>
name <name>

## Asignar VLAN
interface Fa 0/1
switchport access vlan <num>

## Trunk
interface Fa 071
switchport mode trunk
switchport trunk allowed vlan add <num>

Hay que incluir las puertas de enlace de cada VLAN.


